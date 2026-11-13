# CLAUDE.md – Projektlog und Kontext

Hier schreibt **jede Person nach jeder Arbeit** kurz auf, was gemacht wurde. So weiss das ganze Team (und jedes KI-Tool, das diese Datei liest) jederzeit, wo wir stehen.

Prompts an KI-Tools gehören zusätzlich ins [prompt-log.md](prompt-log.md).

## Projekt in Kürze

- Modul 324 (DevOps), Projekt 3 Musikplattform: Web API ohne Frontend.
- Zwei Microservices: **Band-Service** und **Album-Service**. Der Album-Service prüft Bands nur über den Endpoint des Band-Service, nie direkt über die Datenbank.
- Struktur: `Theorie/`, `Dokumentation/`, `Code/band-service`, `Code/album-service`. Einstieg für das Team: [Wegweiser](Wegweiser.md).

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
| 13.11.2026 | Leon | Teams, Sprints, Epic, Projektlog und Prompt-Log eingerichtet | `setup/teamprozess` |
| 13.11.2026 | Leon | Organisation, Repository, Struktur, Kanban Board und Lernjournal-Vorlage eingerichtet | #1 |
