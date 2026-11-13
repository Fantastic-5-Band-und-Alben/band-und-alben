# CLAUDE.md – Projektlog und Kontext

Hier schreibt **jede Person nach jeder Arbeit** kurz auf, was gemacht wurde. So weiss das ganze Team (und jedes KI-Tool, das diese Datei liest) jederzeit, wo wir stehen.

Prompts an KI-Tools gehören zusätzlich ins [prompt-log.md](prompt-log.md).

## Projekt in Kürze

- Modul 324 (DevOps), Projekt 3 Musikplattform: Web API ohne Frontend.
- Zwei Microservices: **Band-Service** und **Album-Service**. Der Album-Service prüft Bands nur über den Endpoint des Band-Service, nie direkt über die Datenbank.
- Struktur: `Theorie/`, `Dokumentation/`, `Code/band-service`, `Code/album-service`. Einstieg für das Team: [Wegweiser](Wegweiser.md).

## Pflicht bei jeder Arbeit

Jeder Pull Request wird automatisch geprüft (`Pflicht-Check`). Ohne diese drei Punkte kann nicht gemergt werden:

1. **Zeitlog:** Zeit pro Task in `Dokumentation/Zeitlogging/<Vorname>.md` (auf 15 Minuten genau).
2. **Projektlog:** Eine Zeile unten im Log dieser Datei – was wurde gemacht.
3. **Prompt-Log:** Jeder KI-Prompt in `prompt-log.md` (Inhalt, Ergebnis, was übernommen wurde). Ohne KI im PR „Keine KI verwendet“ ankreuzen.

Bei Abgaben (T1–T4, P1–P4) zusätzlich ein Eintrag in `Dokumentation/KI-Nachweis.md`.

## Für KI-Tools in diesem Repository

Wenn du als KI-Assistent in diesem Repository arbeitest:

- Trag jeden Auftrag, den du bekommst, in `prompt-log.md` ein (Vorlage dort, Fokus auf den Inhalt).
- Ergänze nach getaner Arbeit eine Zeile im Log unten.
- Erinnere die Person daran, ihre Zeit im Zeitlog einzutragen. Erfinde keine Minuten.
- Arbeite auf einem Branch, nie direkt auf `main`.
- Theorietexte, Entscheide und Begründungen schreibt das Team selbst – unterstütze mit Erklärungen, Vergleichen und Reviews.

## Regeln

- Nie direkt auf `main` – immer Branch und Pull Request mit `Closes #Nummer`.
- Keine Passwörter, Tokens oder Zugangsdaten ins Repo.
- Der API-Contract zwischen den Services wird nur nach Absprache geändert.
- Jede neue Datei in `Theorie/` oder `Dokumentation/` wird im Readme verlinkt.

## Team

| Bereich | Personen |
|---------|----------|
| Product Owner | Leon |
| Entwicklung Band-Service | Leart, Leon |
| Entwicklung Album-Service | Ajna, Levin, Rana |
| CI/CD | Ajna |
| Testing | alle |

## Log

Neuster Eintrag oben. Format: Datum · Wer · Was · Branch/PR

| Datum | Wer | Was wurde gemacht | Branch / PR |
|-------|-----|-------------------|-------------|
| 13.11.2026 | Leon | Zeitlog-Dateien für alle angelegt, 150 Minuten gemeinsame Session für alle. Hinweis: Heute haben wir gemeinsam an einem Gerät (Leon) gearbeitet und viel besprochen – deshalb laufen alle Commits von heute über Leon | #25 |
| 13.11.2026 | Leon | Team „Fantastic 5“ mit Schreibrechten auf Repo und Board, Lehrperson eingeladen, GitHub-Namen im Readme | #25 |
| 13.11.2026 | Leon | Pflicht-Check für Pull Requests (Zeitlog, Projektlog, Prompt-Log) und PR-Vorlage | #25 |
| 13.11.2026 | Leon | Teams, Sprints, Epic, Projektlog und Prompt-Log eingerichtet | #25 |
| 13.11.2026 | Leon | Organisation, Repository, Struktur, Kanban Board und Lernjournal-Vorlage eingerichtet | #1 |
