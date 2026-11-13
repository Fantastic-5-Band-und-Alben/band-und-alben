# Wegweiser – wo ist was?

Kurz und einfach für uns im Team. Das [Readme](Readme.md) ist für die Lehrperson und verlinkt alles. Hier steht, wie wir damit arbeiten.

## Worum geht es?

Wir bauen ein **Web API ohne Frontend** für eine Musikplattform, bestehend aus zwei Teilen:

- **Band-Service:** Bands erfassen (US1) und alle Bands auslesen (US2)
- **Album-Service:** Alben erfassen (US3) – prüft die Band über den Band-Service

Die genauen Anforderungen stehen in den [User Stories](Dokumentation/User_Stories.md).

## Wo ist was?

| Ich suche … | Hier |
|-------------|------|
| Aufgaben – was ist zu tun, wer macht was | [Kanban Board](https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1) |
| Theorieaufträge T1–T4 | Ordner [`Theorie/`](Theorie) – eine Datei pro Auftrag |
| Unsere Dokumentation (Meetings, Branching, Technologie …) | Ordner [`Dokumentation/`](Dokumentation) – eine Datei pro Thema |
| Meine Zeiterfassung | [`Dokumentation/Zeitlogging/`](Dokumentation/Zeitlogging/Readme.md) – eine Datei pro Person |
| Den Code | Ordner [`Code/`](Code/Readme.md) – `band-service` und `album-service` |
| Termine und Abgaben | [Readme](Readme.md#termine-und-abgaben) |
| KI-Nutzung festhalten | [`Dokumentation/KI-Nachweis.md`](Dokumentation/KI-Nachweis.md) |
| Mein Lernjournal (freiwillig) | eigenes Repo – siehe unten |

## Erste Schritte (einmalig)

1. **Einladung annehmen:** Du bekommst eine Mail von GitHub für die Organisation *Fantastic-5-Band-und-Alben* → annehmen.
2. **Repo klonen:**
   ```
   git clone https://github.com/Fantastic-5-Band-und-Alben/band-und-alben.git
   ```
3. **Zeitlogging anlegen:** [`Vorlage.md`](Dokumentation/Zeitlogging/Vorlage.md) kopieren als `Dokumentation/Zeitlogging/DeinVorname.md` und in der [Übersicht](Dokumentation/Zeitlogging/Readme.md) eintragen.
4. **Im Readme** deinen Namen, dein GitHub-Konto und deine Rolle in die Team-Tabelle eintragen.
5. **Lernjournal (freiwillig):** Öffne die [Lernjournal-Vorlage](https://github.com/Fantastic-5-Band-und-Alben/lernjournal-vorlage) → **Use this template** → als Owner **dein eigenes Konto** wählen, **Private** → Lehrperson unter *Settings → Collaborators* einladen → Link im Readme unter „Andere Links“ eintragen.

## So arbeiten wir

1. **Aufgabe nehmen:** Auf dem Board eine Karte aus *To Do* nehmen, dich zuweisen (*Assignees*) und auf *In Progress* schieben.
2. **Branch erstellen:** Namensregeln stehen in der [Branching-Strategie](Dokumentation/Branching_Strategie.md) (legen wir gemeinsam fest).
3. **Arbeiten und committen.**
4. **Pull Request öffnen:** Im PR `Closes #Nummer` schreiben – dann schliesst sich die Karte beim Merge automatisch. Karte auf *Review* schieben.
5. **Review:** Jemand anderes schaut den PR an und merged ihn → Karte landet auf *Done*.
6. **Zeit loggen:** Am Ende des Tages pro Task, auf 15 Minuten genau (ca. 160–180 Min. pro Modultag).

## Board-Phasen

| Phase | Bedeutung |
|-------|-----------|
| Backlog | erfasst, noch nicht bereit |
| To Do | bereit, kann jemand nehmen |
| In Progress | jemand arbeitet daran |
| Review | Pull Request offen, wartet auf Review |
| Done | gemergt und erledigt |

## Regeln

- Jede neue Datei in `Theorie/` oder `Dokumentation/` wird im [Readme](Readme.md) verlinkt.
- Keine Passwörter, Tokens oder Zugangsdaten ins Repo (auch nicht in `.env`).
- KI darf helfen (erklären, vergleichen, reviewen), aber nicht die Abgabe schreiben. Jede Abgabe hat einen kurzen [KI-Nachweis](Dokumentation/KI-Nachweis.md) – auch „keine KI verwendet“.
- In den Fachgesprächen muss **jede Person** selbst erklären können – auch Teile, die andere gemacht haben.
