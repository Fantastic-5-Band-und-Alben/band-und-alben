# KI-Nachweis

Das ist die **einzige Datei** für unsere KI-Nutzung. Ein separates Prompt-Log gibt es nicht mehr.

**So funktioniert es**
- Pro Abgabe (T1–T4, P1–P4) gibt es **einen** Eintrag mit dem [offiziellen Template](https://ch-tbz-it.gitlab.io/Stud/m324/Projekt/KI-Nachweis_Template/). Darin steht ein aussagekräftiger KI-Einsatz mit Beleg, keine vollständigen Chats.
- Wenn mehrere Personen an einer Abgabe mit KI gearbeitet haben, ergänzt jede Person den Eintrag dieser Abgabe.
- Ohne KI: In der Tabelle „Nein – keine KI verwendet“ eintragen. Der Verständnisnachweis im Fachgespräch gilt trotzdem.

| Abgabe | KI verwendet? | Eintrag |
|--------|---------------|---------|
| P1 Infrastruktur | Ja | [P1](#p1--projekt-setup-und-infrastruktur) |
| T1 DevOps-Kultur | Ja | [T1](#t1--devops-kultur) |
| T2 DevOps-Prozesse | | |
| T3 Continuous Integration | | |
| P2 Applikation v1 | | |
| P3 / P3b CI und Artefakte | | |
| T4 Continuous Deployment | | |
| P4 Continuous Deployment | | |

---

## P1 – Projekt-Setup und Infrastruktur

_Eintrag von Leon_

### KI-Nachweis

- Auftrag: P1 Projekt Setup und Infrastruktur
- KI-Tool: Claude Code
- Zweck der Nutzung: Struktur, Board und Vorlagen nach den Modulunterlagen aufsetzen, Fragen zur Aufgabenstellung klären
- Eigener Startplan ohne KI: GitHub-Organisation selbst angelegt, ein Repo für die Gruppe, Rollen im Team besprochen, Meetings am Freitag, C# für den Band-Service

### KI-Nutzung

- Promptauszug oder Kurzfassung: Struktur nach P1 vorbereiten, Lernjournal pro Person, Wegweiser fürs Team, Sprints und Epic aufs Board, automatischer Check für Zeitlog und Projektlog. Fragen: Was ist Ziel und Fokus des Projekts? Welche Rollen braucht es? Eine oder zwei Datenbanken? Ein oder mehrere Repos?
- Wichtigste KI-Antwort: Ordnerstruktur, Board mit Phasen und Sprints, Vorlagen für T1–T4 und D2–D4, automatischer Check bei jedem Pull Request. Der Fokus liegt auf dem DevOps-Prozess, nicht auf der App.
- Übernommene Vorschläge: Struktur, Board, Vorlagen, Pflicht-Check
- Angepasste oder verworfene Vorschläge:
  - Lernjournal-Vorlage verworfen, jede Person hat ihr eigenes Repo angelegt
  - User Stories zuerst vom Board genommen, dann für P2 wieder eingeplant
  - P1-Übersicht war zu lang und zu formell, wir haben sie vereinfacht
  - Eigenes Prompt-Log wieder abgeschafft (Feedback der Lehrperson: redundant), jetzt nur noch dieser KI-Nachweis
  - Technologie und Rollen hat das Team entschieden, nicht die KI

### Validierung

- Prüfung durch Tests, Logs, Pipeline, Review, Screenshot oder Quelle: Abgleich mit P1, D1–D5 und Projekt 3, Links in der P1-Übersicht geprüft, Pflicht-Check mit grünem und rotem Fall getestet, Rechte pro Person auf GitHub kontrolliert
- Resultat der Prüfung: Die Members hatten nur Leserechte und konnten nicht pushen
- Korrekturen nach der Prüfung: Team „Fantastic 5“ mit Schreibrechten angelegt

### Eigenleistung

- Was habe ich selbst entschieden? Rollen, Sprints von einer Woche, Meetings am Freitag, C# für den Band-Service, Absprache über einen API-Contract, Verteilung der Stories auf die Sprints
- Was kann ich in einem Code-Walkthrough, Pipeline-Walkthrough oder Fachgespräch erklären? _Leon ergänzen_

### Reflexion

- Wo hat KI geholfen? Beim Lesen der vielen Unterlagen und beim schnellen Aufsetzen von Repo und Board
- Wo war KI falsch, unvollständig oder zu allgemein? Die ersten Texte waren zu lang und zu formell, und eine Vorlage war unnötig
- Was habe ich durch den KI-Einsatz fachlich gelernt? _Leon ergänzen_

### Selbstprüfung ohne KI

- Welchen Zusammenhang habe ich nach dem Schliessen des Chats selbst erklärt oder auf einen veränderten Fall angewendet? _Leon ergänzen_
- Was gelang bereits, und wobei brauchte ich noch Unterstützung? _Leon ergänzen_
- Was übe ich als Nächstes? _Leon ergänzen_

---

## T1 – DevOps-Kultur

_Eintrag von Leon. Andere aus dem Team ergänzen, falls sie KI genutzt haben._

### KI-Nachweis

- Auftrag: T1 DevOps-Kultur: CALMS und The Three Ways
- KI-Tool: Claude Code
- Zweck der Nutzung: Eigene Antworten reviewen lassen (Korrektheit, was fehlt), Grammatik und Satzstellung verbessern, die Teile des Teams in einem Dokument zusammenführen.
- Eigener Startplan ohne KI: Aufgaben im Team aufgeteilt (Leon Culture und Automation, Levin Lean, Rana Measurement und Sharing, Leart The Three Ways), Unterlagen gelesen, Antworten selbst geschrieben

### KI-Nutzung

- Promptauszug oder Kurzfassung: „Hier meine Antworten zu Culture und Automation in meinen Worten. Grammatik anpassen, Struktur verbessern, aber es sollen meine Worte bleiben. Sag mir, was ich vergessen habe.“
- Wichtigste KI-Antwort: Die Antwort auf „Warum ist eine Pipeline allein kein DevOps?“ trifft den Punkt der Unterlage nicht. Automation umfasst mehr als Tests (Artefakte, Deployment, Monitoring). Die wöchentlichen Releases bei TechNova sind das stärkste Beispiel. Bei Lean und The Three Ways fehlt noch der Bezug zu TechNova.
- Übernommene Vorschläge: Lücken selbst ergänzt (Fehler werden mitautomatisiert, Deployment und Monitoring, wöchentliche Releases, Rolle des Managements)
- Angepasste oder verworfene Vorschläge: _Leon ergänzen_

### Validierung

- Prüfung durch Tests, Logs, Pipeline, Review, Screenshot oder Quelle: Hinweise mit der Unterlage [CALMS](https://ch-tbz-it.gitlab.io/Stud/m324/Kultur/CALMS/) und der Fallstudie abgeglichen
- Resultat der Prüfung: Die Unterlage sagt bei Automation, wer nur automatisiert, „automatisiert im Wesentlichen die Fehler komplett durch“. Meine erste Antwort ging in eine andere Richtung.
- Korrekturen nach der Prüfung: Antwort zu „Pipeline allein ist kein DevOps“ neu geschrieben

### Eigenleistung

- Was habe ich selbst entschieden? Inhalt und Beispiele meiner Abschnitte, Aufteilung im Team. Die KI hat nur Grammatik und Satzstellung überarbeitet.
- Was kann ich in einem Code-Walkthrough, Pipeline-Walkthrough oder Fachgespräch erklären? _Leon ergänzen_

### Reflexion

- Wo hat KI geholfen? Beim Finden von Lücken in meinen Antworten
- Wo war KI falsch, unvollständig oder zu allgemein? _Leon ergänzen_
- Was habe ich durch den KI-Einsatz fachlich gelernt? _Leon ergänzen_

### Selbstprüfung ohne KI

- Welchen Zusammenhang habe ich nach dem Schliessen des Chats selbst erklärt oder auf einen veränderten Fall angewendet? _Leon ergänzen (z. B. nach dem FG1)_
- Was gelang bereits, und wobei brauchte ich noch Unterstützung? _Leon ergänzen_
- Was übe ich als Nächstes? _Leon ergänzen_

---

## Vorlage (offizielles Template, pro Abgabe kopieren)

```
## Abgabe – Titel

_Eintrag von …_

### KI-Nachweis

- Auftrag:
- KI-Tool:
- Zweck der Nutzung:
- Eigener Startplan ohne KI:

### KI-Nutzung

- Promptauszug oder Kurzfassung:
- Wichtigste KI-Antwort:
- Übernommene Vorschläge:
- Angepasste oder verworfene Vorschläge:

### Validierung

- Prüfung durch Tests, Logs, Pipeline, Review, Screenshot oder Quelle:
- Resultat der Prüfung:
- Korrekturen nach der Prüfung:

### Eigenleistung

- Was habe ich selbst entschieden?
- Was kann ich in einem Code-Walkthrough, Pipeline-Walkthrough oder Fachgespräch erklären?

### Reflexion

- Wo hat KI geholfen?
- Wo war KI falsch, unvollständig oder zu allgemein?
- Was habe ich durch den KI-Einsatz fachlich gelernt?

### Selbstprüfung ohne KI

- Welchen Zusammenhang habe ich nach dem Schliessen des Chats selbst erklärt oder auf einen veränderten Fall angewendet?
- Was gelang bereits, und wobei brauchte ich noch Unterstützung?
- Was übe ich als Nächstes?
```
