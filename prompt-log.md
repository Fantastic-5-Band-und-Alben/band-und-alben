# Prompt-Log

Jeder Prompt an ein KI-Tool wird hier dokumentiert. Fokus auf den **Inhalt**: Was wollten wir wissen, was kam raus, was haben wir damit gemacht?

Für Abgaben zusätzlich einen ausgewählten Eintrag in den [KI-Nachweis](Dokumentation/KI-Nachweis.md) übernehmen.

## Vorlage

```
### TT.MM.JJJJ – Wer – Thema
- Tool:
- Zweck:
- Prompt (Inhalt):
- Ergebnis:
- Übernommen / angepasst / verworfen:
- Geprüft durch:
```

---

## Einträge (neuster oben)

### 13.11.2026 – Leon – P1-Abgabe als Übersicht
- Tool: Claude Code
- Zweck: Der Lehrperson P1 auf einer Seite zeigen können
- Prompt (Inhalt): Ein Markdown für P1 mit allen Verlinkungen erstellen, damit die Lehrperson direkt sieht, dass alles vorhanden ist.
- Ergebnis: Dokumentation/P1_Abgabe.md mit Abgabekriterien, Links, Team, Arbeitsweise und offenen Punkten – danach einfacher und persönlicher umgeschrieben
- Übernommen / angepasst / verworfen: übernommen; offene Punkte ehrlich als offen markiert
- Geprüft durch: Stand der Karten und der Einladung über GitHub abgefragt

### 13.11.2026 – Leon – Zeitlog-Dateien
- Tool: Claude Code
- Zweck: Zeitlogging für alle starten (Teil der P1-Abgabe)
- Prompt (Inhalt): Warum schon Zeitlog ohne Coding? Danach: Zeitlog-Datei für alle anlegen; heute läuft alles über Leon, weil wir zusammen an einem Gerät gearbeitet haben.
- Ergebnis: D4 verlangt Zeitlog ab Tag 1 für alle Tätigkeiten (auch Planung, Meetings, Theorie). Dateien für Leart, Ajna, Levin, Rana mit der heutigen Setup-Session; Minuten trägt jede Person selbst ein.
- Übernommen / angepasst / verworfen: übernommen
- Geprüft durch: Abgleich mit P1 und D4

### 13.11.2026 – Leon – P1-Check und Zugriffe
- Tool: Claude Code
- Zweck: Prüfen, ob P1 vollständig ist, und fehlende Zugriffe einrichten
- Prompt (Inhalt): Stand P1 gegen die Abgabekriterien prüfen. Danach: Team mit Schreibrechten anlegen, Lehrperson Schreibrechte auf Repo und Board geben, GitHub-Namen im Readme eintragen.
- Ergebnis: Members hatten nur Leserechte → Team „Fantastic 5“ mit Schreibrechten; Lehrperson mit Schreibrechten eingeladen (Repo und Board); GitHub-Namen im Readme
- Übernommen / angepasst / verworfen: übernommen
- Geprüft durch: Berechtigungen pro Person über GitHub abgefragt

### 13.11.2026 – Leon – Pflichten automatisch prüfen
- Tool: Claude Code
- Zweck: Sicherstellen, dass Zeitlog, Projektlog und Prompt-Log bei jeder Arbeit nachgeführt werden
- Prompt (Inhalt): Bei jeder Arbeit soll Pflicht sein, dass Zeitlog und Prompt-/KI-Dokumentation gemacht werden. Lernjournal-Vorlage entfernen, Stand P1 prüfen.
- Ergebnis: GitHub Action „Pflicht-Check“ auf jedem Pull Request, PR-Vorlage mit Checkliste, Regeln in CLAUDE.md, Check als Pflicht für `main`
- Übernommen / angepasst / verworfen: übernommen
- Geprüft durch: Check läuft auf PR #25

### 13.11.2026 – Leon – Teamprozess, Sprints und Epic
- Tool: Claude Code
- Zweck: Teamaufteilung, Sprints und erstes Epic auf dem Board einrichten
- Prompt (Inhalt): Rollen (PO, Entwicklung Band-/Album-Service, CI/CD, Testing) auf dem Board abbilden, Sprints ab nächster Woche, User Stories vorerst vom Board nehmen, Epic mit Vorschlag für das Endprodukt erstellen, Projektlog und Prompt-Log anlegen, Arbeit nur über Branches und Pull Requests.
- Ergebnis: Team-Feld und Sprint-Feld auf dem Board, Epic mit Produktvorschlag, CLAUDE.md und prompt-log.md
- Übernommen / angepasst / verworfen: Epic-Vorschlag wird vom PO überarbeitet
- Geprüft durch: Board und Repository im Browser kontrolliert

### 13.11.2026 – Leon – Projektfragen
- Tool: Claude Code
- Zweck: Aufgabenstellung verstehen
- Prompt (Inhalt): Was ist Ziel und Fokus des Projekts? Welche Rollen verlangt die Aufgabenstellung? Dürfen wir das Projektziel selbst wählen? Eine oder zwei Datenbanken? Monorepo oder mehrere Repos?
- Ergebnis: Fokus ist der DevOps-Prozess (Tests, CI, Artefakt, Deployment, Rollback), nicht die App. Projekt kann mit vergleichbaren User Stories vorgeschlagen werden. Gleiche DB erlaubt, getrennte empfohlen. Mono- vs. Multirepo ist Teil von T3.
- Übernommen / angepasst / verworfen: Entscheide zu DB und Repo-Struktur trifft das Team nach T3
- Geprüft durch: Abgleich mit den Modulunterlagen (Projekt/Readme, P1, Projekt3_Musikplattform, T3)

### 13.11.2026 – Leon – Projekt-Setup
- Tool: Claude Code
- Zweck: Repository und Dokumentationsstruktur nach P1 aufsetzen
- Prompt (Inhalt): Struktur gemäss P1 und Modulunterlagen vorbereiten (Readme, Theorie, Dokumentation, Code), Kanban Board, Zeitlogging, Lernjournal pro Person, Wegweiser für das Team.
- Ergebnis: Repository mit Vorlagen T1–T4, D2–D4, KI-Nachweis, Board mit Phasen und Meilensteinen, Lernjournal-Vorlage
- Übernommen / angepasst / verworfen: Struktur übernommen; Inhalte (Theorie, Entscheide) schreibt das Team selbst
- Geprüft durch: Vergleich mit P1-Abgabekriterien
