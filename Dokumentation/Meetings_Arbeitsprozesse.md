# D3 – Meetings / Arbeitsprozesse

_Themenblock gemäss D1. Muss definiert sein, bevor wir praktisch arbeiten. Laufend verbessern._

## Rollen

### Verantwortungsbereiche

Verantwortlich heisst nicht „macht alles allein“ – Aufgaben rotieren, alle machen auch Code, CI/CD und Theorie.

| Bereich | Personen | Verantwortung |
|---------|----------|---------------|
| Product Owner | Leon | Epic und User Stories, Prioritäten, Board aktuell, Ansprechperson der Lehrperson |
| Entwicklung Band-Service | Leart, Leon | US zu Bands, API-Contract des Band-Service |
| Entwicklung Album-Service | Ajna, Levin, Rana | US zu Alben, Aufruf des Band-Service |
| CI/CD | Ajna | Pipelines, Artefakt-Repository, Deployment, Rollback |
| Testing | alle | Unit Tests zum eigenen Code, Review der Tests der anderen |

### Meeting-Rollen (wechseln jede Woche)

| Sprint | Moderation | Protokoll | Timekeeper |
|--------|------------|-----------|------------|
| Sprint 1 | | | |
| Sprint 2 | | | |
| Sprint 3 | | | |

## Meetings

Wir arbeiten in Sprints von einer Woche. Das Team-Meeting ist **jeden Freitag**.

| Meeting | Wann | Dauer | Inhalt / Agenda | Wer |
|---------|------|-------|-----------------|-----|
| Sprint-Meeting | Freitag | | 1. Rückblick letzter Sprint (Review) · 2. Was lief gut, was verbessern wir? (Retro) · 3. Planung nächster Sprint (Karten ziehen, zuweisen) | alle |
| Austausch unter der Woche | | | | |
| Teamtermin mit Lehrperson | wöchentlich, 30 Min. | 30 Min. | Fachgespräche W2, 5, 6, 9 · Lernchecks W3, 7 | alle |

### So läuft ein Freitag (Modultag)

1. **Auftrag lesen und verstehen** (30 Min.): Jede Person liest den Auftrag des Tages für sich.
2. **Daily:** Wir sprechen das Thema zusammen durch und teilen auf, wer was macht.
3. **Arbeiten:** Jede Person arbeitet an ihrem Teil. Den schriftlichen Teil teilen wir auf, verstehen muss aber jede Person alles (Fachgespräch).
4. **Zusammentragen:** Am Schluss tragen wir alles bei einer Person zusammen. Sie macht den Pull Request.
5. **Retro** am Ende des Tages: Was lief gut, was machen wir nächstes Mal besser?

## Arbeitsprozess

- Aufgaben stehen auf dem [Kanban Board](https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1) mit Sprint und Team.
- Phasen: Backlog → To Do → In Progress → Review → Done
- **Nie direkt auf `main`**: immer Branch → Pull Request mit `Closes #Nummer` → Review durch eine andere Person → Merge.
- Was gemacht wurde, kommt ins [CLAUDE.md](../CLAUDE.md), KI-Nutzung pro Abgabe in den [KI-Nachweis](KI-Nachweis.md).
- Die Services arbeiten gegen einen festgelegten API-Contract; Änderungen nur nach Absprache.
- **Texte schreiben wir von Hand.** KI darf nur Grammatik und Satzstellung überarbeiten. Das steht jeweils in der Abgabe und im [KI-Nachweis](KI-Nachweis.md).
- Immer genug Tasks in To Do, damit niemand Leerlauf hat.
- Weg einer Anforderung bis zur Auslieferung: _ergänzen_

## Daily-Protokolle

| Datum | Thema | Wer macht was |
|-------|-------|---------------|
| 27.11.2026 | T1 DevOps-Kultur und T2 DevOps-Prozesse | T1: Leon Culture und Automation, Levin Lean, Rana Measurement und Sharing, Leart The Three Ways. T2: Ajna zusammen mit Leart. Am Schluss trägt Leon alles zusammen und macht den Pull Request. |

## Protokolle und Verbesserungen

| Datum | Was lief gut? | Was verbessern wir? | Massnahme |
|-------|---------------|---------------------|-----------|
| | | | |

## Feedback aus Fachgesprächen

| Datum | Feedback | Nächster Lernschritt / Aufgabe |
|-------|----------|--------------------------------|
| | | |
