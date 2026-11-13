# Applikation / Technologie

_Themenblock gemäss D1. Vom Team zu entscheiden und zu begründen – die Begründung muss im Fachgespräch verteidigt werden können._

## Architektur

Zwei Microservices, behandelt als separate Projekte:

| Microservice | Ordner | User Stories | Datenbank |
|--------------|--------|--------------|-----------|
| Bands | [Code/band-service](../Code/band-service/Readme.md) | US1, US2 | _festlegen_ |
| Alben | [Code/album-service](../Code/album-service/Readme.md) | US3 | _festlegen_ |

Der Album-Service validiert die Band über den Endpoint des Band-Service (US2), nicht direkt über die Datenbank.

_Skizze der Architektur einfügen._

## Programmiersprache und Framework

Gilt pro Microservice – beide gleich oder unterschiedlich (unterschiedlich = Mehraufwand bei CI/CD).

| Kriterium | Variante A | Variante B |
|-----------|------------|------------|
| Vorwissen im Team | | |
| Unit-Test-Framework | | |
| Eignung für Web APIs | | |
| CI/CD mit GitHub Actions | | |

**Entscheid:** …

**Begründung:** …

## Datenbank

| Kriterium | Variante A | Variante B |
|-----------|------------|------------|
| Cloud-Hosting (z.B. MongoDB Atlas, AWS RDS) | | |
| Lokale Entwicklung (Docker) | | |
| Passend zum Datenmodell | | |

**Entscheid:** …

**Begründung:** …

## Tests

- Unit-Test-Framework: …
- Weitere Teststufen: …

## Risiken

- …
