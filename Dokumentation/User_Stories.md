# User Stories – Projekt 3: Musikplattform

Wir erstellen eine Applikation, mit der man Bands und Alben verwalten kann. Rolle: Anbieter einer Plattform, auf der man Musik kaufen kann. Nur Backend – jede User Story ist ein Endpoint eines Web APIs.

Die User Stories sind vom Modul vorgegeben. Jede Story ist zusätzlich ein Issue auf dem [Kanban Board](https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1).

| Nr. | Microservice | User Story | Endpoint | Issue |
|-----|--------------|------------|----------|-------|
| US1 | Bands | Band erfassen | _festlegen_ | #15 |
| US2 | Bands | Alle Bands auslesen | _festlegen_ | #16 |
| US3 | Alben | Alben erfassen | _festlegen_ | #17 |

**Wichtig:** Beide Microservices sind separate Projekte. Sie dürfen dieselbe Datenbank verwenden, aber nicht die Daten des anderen Service laden. Der Endpoint von US3 muss die Band über den Endpoint von US2 auslesen, nicht direkt aus der Datenbank.

---

## Microservice 1: Verwaltung von Bands

### US1 – Band erfassen

Als Administrator des Systems möchte ich neue Bands mit den relevanten Eigenschaften erfassen können, damit die Banddaten zentral verwaltet und für weitere Prozesse genutzt werden können.

**Abnahmekriterien**

1. Der Administrator kann den *Namen* der Band angeben (z. B. "Ghost DX").
2. Der Administrator kann das *Genre* der Band angeben (z. B. "Nu Metal").
3. Der Administrator kann das *Gründungsdatum* der Band eingeben (z. B. "15.05.2021").
4. Der Administrator kann die Anzahl der *Bandmitglieder* eingeben (z. B. 5).
5. Der Administrator kann optional ein *Auflösungsdatum* eingeben. Wenn kein Datum eingetragen wird, gilt die Band als aktiv (NULL-Wert).
6. Während der Erfassung wird eine eindeutige ID automatisch für jede Band generiert.
7. Nach erfolgreicher Erfassung wird die Band in der Systemübersicht angezeigt.
8. Alle Felder sind korrekt validiert (z. B. das Auflösungsdatum muss nach dem Gründungsdatum liegen).
9. Fehlerhafte Eingaben führen zu klaren Fehlermeldungen, die den Administrator zur Korrektur anleiten.

### US2 – Alle Bands auslesen

Als Administrator des Systems möchte ich alle erfassten Bands auslesen können, damit ich eine Übersicht der bereits erfassten Bands erhalte.

**Abnahmekriterien**

1. Der Administrator kann eine Liste aller erfassten Bands abrufen.
2. Alle Felder der Bands (Name, Genre, Gründungsdatum, Anzahl Bandmitglieder, Auflösungsdatum, eindeutige ID) werden vollständig zurückgeliefert.
3. Die angezeigte Liste ist übersichtlich und strukturiert.
4. Bands, die kein Auflösungsdatum haben, werden als "aktiv" angezeigt.
5. Der Abruf funktioniert auch bei einer grossen Anzahl von erfassten Bands ohne Verzögerungen.
6. Falls keine Bands vorhanden sind, wird eine entsprechende Meldung angezeigt.
7. Fehlerhafte Abfragen führen zu einer klaren Fehlermeldung.

## Microservice 2: Verwaltung von Alben

### US3 – Alben erfassen

Als Administrator des Systems möchte ich Alben für eine Band erfassen können, damit die Albeninformationen zentral verwaltet und mit den entsprechenden Bands verknüpft werden können.

**Abnahmekriterien**

1. Der Administrator kann das *Veröffentlichungsdatum* des Albums eingeben (z. B. "21.06.2024").
2. Der Administrator kann den *Titel* des Albums angeben (z. B. "School Rocks").
3. Der Administrator kann die *Band* auswählen, die das Album herausgegeben hat.
4. Der Administrator kann das *Label* eingeben, das das Album produziert hat (z. B. "Zurich Musics AG").
5. Der Administrator kann den *Verkaufspreis* des Albums festlegen.
6. Eine Validierung stellt sicher, dass alle Felder korrekt ausgefüllt sind (z. B. positive Werte für den Verkaufspreis).
7. Nach erfolgreicher Erfassung wird das Album in der Systemübersicht angezeigt, inklusive aller zugehörigen Informationen (Band, Veröffentlichungsdatum, Label, Preis).
8. Fehlerhafte Eingaben führen zu klaren Fehlermeldungen, die den Administrator zur Korrektur anleiten.

**Wichtig:** Dieser Endpoint verwendet den ersten Microservice, um die Eingabe der Band zu validieren, muss also dessen Endpoint aufrufen.
