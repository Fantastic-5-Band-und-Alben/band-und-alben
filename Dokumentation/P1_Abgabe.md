# P1 – Abgabe: Projekt Setup und Infrastruktur

Gruppe **Fantastic 5** · Projekt 3: Musikplattform (Band und Alben) · Stand: 13.11.2026

Alles auf einen Blick – jeder Punkt der Abgabe mit direktem Link.

| | |
|---|---|
| Repository | https://github.com/Fantastic-5-Band-und-Alben/band-und-alben |
| Kanban Board | https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1 |
| Organisation | https://github.com/Fantastic-5-Band-und-Alben |

## Abgabekriterien

| Kriterium | Status | Nachweis |
|-----------|--------|----------|
| Ordnerstruktur | ✅ | [Readme.md](../Readme.md) · [Theorie/](../Theorie) · [Dokumentation/](../Dokumentation) · [Code/](../Code) |
| Readme mit Verlinkungen | ✅ | [Readme.md](../Readme.md) – verlinkt Theorie, Themenblöcke, Code, Board, Zeitlogging, Lernjournale |
| Zeitlogging | ✅ | [Übersicht](Zeitlogging/Readme.md) – eine Datei pro Person: [Leon](Zeitlogging/Leon.md) · [Leart](Zeitlogging/Leart.md) · [Ajna](Zeitlogging/Ajna.md) · [Levin](Zeitlogging/Levin.md) · [Rana](Zeitlogging/Rana.md) |
| Lehrperson: Schreibrechte Repository | ⏳ | Eingeladen mit Schreibrechten (`pat-teacher`) – Einladung noch annehmen |
| Lehrperson: Schreibrechte Zeitlogging | ⏳ | Zeitlogging liegt im Repository → mit der Einladung oben abgedeckt |
| Lehrperson: Lernjournale (freiwillig) | ✅ | Privates Repo pro Person, Links im [Readme](../Readme.md#andere-links) |
| Kanban Board mit sinnvollen Phasen | ✅ | [Board](https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1) – Backlog → To Do → In Progress → Review → Done |

## Was wir zusätzlich eingerichtet haben

| Was | Wozu | Link |
|-----|------|------|
| Sprints (1 Woche, Start Freitag) | Planung im Freitags-Meeting | Feld „Sprint“ auf dem [Board](https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1) |
| Team-Feld auf dem Board | Wer ist für welchen Bereich zuständig | Feld „Team“ auf dem [Board](https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1) |
| Meilensteine pro Abgabewoche | Abgaben und Fachgespräche im Blick | [Meilensteine](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/milestones) |
| Epic | Ziel des Endprodukts | [#24 Musikplattform-Backend](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/issues/24) |
| Schutz von `main` | Änderungen nur über Pull Request mit Review | [Branch-Regeln](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/rules) |
| Pflicht-Check | Jeder Pull Request muss Zeitlog, Projektlog und Prompt-Log nachführen | [Workflow](../.github/workflows/pflicht-check.yml) · [Läufe](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/actions/workflows/pflicht-check.yml) |
| Projektlog | Was wurde wann von wem gemacht | [CLAUDE.md](../CLAUDE.md) |
| Prompt-Log | Jeder KI-Prompt mit Inhalt und Ergebnis | [prompt-log.md](../prompt-log.md) |
| Vorlagen | User Story, Aufgabe, Pull Request | [.github](../.github) |
| Wegweiser | Einstieg fürs Team: wo ist was, wie arbeiten wir | [Wegweiser.md](../Wegweiser.md) |

## Teamorganisation

| Name | GitHub | Rolle |
|------|--------|-------|
| Leon | [@LeonWWImmo](https://github.com/LeonWWImmo) | Product Owner, Entwicklung Band-Service |
| Leart | [@Leart165](https://github.com/Leart165) | Entwicklung Band-Service |
| Ajna | [@aj-kry](https://github.com/aj-kry) | CI/CD, Entwicklung Album-Service |
| Levin | [@Le999vin](https://github.com/Le999vin) | Entwicklung Album-Service |
| Rana | [@ranaaksoy](https://github.com/ranaaksoy) | Entwicklung Album-Service |

Testing machen alle. Details zu Rollen und Meetings: [D3 Meetings / Arbeitsprozesse](Meetings_Arbeitsprozesse.md).

## Projekt- und Technologieentscheid

| Punkt | Status | Dokument |
|-------|--------|----------|
| Projekt | ✅ Projekt 3 Musikplattform, 2 Microservices | [User Stories](User_Stories.md) |
| Architektur | ✅ Band-Service und Album-Service, Kommunikation nur über die API | [Applikation / Technologie](Applikation_Technologie.md) |
| Band-Service | 🟡 C# gesetzt – Framework, Datenbank, Test-Framework und Begründung folgen | [Applikation / Technologie](Applikation_Technologie.md) |
| Album-Service | ⏳ in Abklärung im Team | [Applikation / Technologie](Applikation_Technologie.md) |
| Toolwahl (GitHub, Actions, Projects) | ⏳ Begründung folgt | [Infrastruktur](Infrastruktur.md) |

## Offen bis zum Fachgespräch FG1

- [ ] Lehrperson nimmt Einladung an ([#2](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/issues/2))
- [ ] Technologieentscheid mit Begründung ([#5](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/issues/5))
- [ ] Toolwahl begründen ([#4](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/issues/4))
- [ ] Meetings: Agenda und Ablauf ergänzen ([#6](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/issues/6))
- [ ] KI-Nachweis P1 ([#9](https://github.com/Fantastic-5-Band-und-Alben/band-und-alben/issues/9))

## Für das Fachgespräch FG1

| Die Lehrperson will sehen … | Hier zeigen |
|-----------------------------|-------------|
| Repository, Kanban und Teamorganisation | [Readme](../Readme.md) · [Board](https://github.com/orgs/Fantastic-5-Band-und-Alben/projects/1) · [D3](Meetings_Arbeitsprozesse.md) |
| Begründung der Toolwahl | [Infrastruktur](Infrastruktur.md) |
| Weg einer Anforderung bis zur Auslieferung | [Infrastruktur – Weg einer Anforderung](Infrastruktur.md#weg-einer-anforderung-bis-zur-auslieferung) · [Wegweiser – So arbeiten wir](../Wegweiser.md#so-arbeiten-wir) |
| KI-Nutzung | [KI-Nachweis](KI-Nachweis.md) · [Prompt-Log](../prompt-log.md) |
