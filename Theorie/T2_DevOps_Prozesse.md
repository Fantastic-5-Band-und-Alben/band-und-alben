# T2 – DevOps-Prozesse

_Bearbeitet von: Ajna (Teil 1–3), Leart · Abgabe: Woche 2 (FG1)_

> Von Hand geschrieben. Grammatik und Satzstellung hat danach Claude (KI) überarbeitet. Bei jedem Abschnitt steht, wer ihn geschrieben hat.

## 1. Was ist der SDLC und wie gliedert er sich?

_Geschrieben von Ajna_

Der Software Development Life Cycle (SDLC) beschreibt den gesamten Lebenszyklus einer Software – von der ersten Idee über die Entwicklung bis zum Betrieb und zur Wartung. Sein Ziel ist es, Software strukturiert, effizient und in guter Qualität zu entwickeln.

### Phasen des SDLC

| Phase                             | Beschreibung                                                               |
| --------------------------------- | -------------------------------------------------------------------------- |
| 1. Planung (Planning)             | Ziele, Zeitplan, Kosten und benötigte Ressourcen festlegen.                |
| 2. Anforderungsanalyse (Analysis) | Ermitteln, welche Funktionen und Anforderungen die Software erfüllen muss. |
| 3. Entwurf (Design)               | Architektur, Datenbank, Schnittstellen und Benutzeroberfläche planen.      |
| 4. Entwicklung (Implementation)   | Die geplanten Funktionen programmieren.                                    |
| 5. Testen (Testing)               | Die Software auf Fehler, Sicherheit und Funktionalität überprüfen.         |
| 6. Bereitstellung (Deployment)    | Die Software in der Zielumgebung veröffentlichen.                          |
| 7. Wartung (Maintenance)          | Fehler beheben, Updates durchführen und die Software weiterentwickeln.     |

Je nach Modell können die Phasen unterschiedlich benannt, wiederholt oder parallel durchgeführt werden. Am Ende des Lebenszyklus kann die Software auch ausser Betrieb genommen werden.

### Wie wird der SDLC in einem Projekt angewendet und gesteuert?

Der SDLC dient als Grundlage für die Organisation eines Softwareprojekts. Aufgaben, Verantwortlichkeiten, Anforderungen und Fortschritte werden beispielsweise über ein Kanban-Board, Tickets, Meilensteine und regelmässige Besprechungen gesteuert. Tests und Code-Reviews helfen dabei, die Qualität sicherzustellen.

Es gibt unterschiedliche Vorgehensmodelle:

- **Wasserfallmodell:** Die Phasen werden hauptsächlich nacheinander durchgeführt.
- **Agile Entwicklung (z. B. Scrum):** Die Phasen werden in kurzen Iterationen wiederholt. Anforderungen können laufend angepasst werden.

## 2. Was ist der DevOps Lifecycle und wie ist er strukturiert?

_Geschrieben von Ajna_

Der DevOps Lifecycle beschreibt einen kontinuierlichen Prozess, der die Softwareentwicklung (Development, Dev) und den IT-Betrieb (Operations, Ops) miteinander verbindet. Im Mittelpunkt stehen die Zusammenarbeit, Automatisierung und kontinuierliche Verbesserung.

Damit ist gemeint, dass die Softwareentwicklung (Dev) und der IT-Betrieb (Ops) eng zusammenarbeiten, anstatt unabhängig voneinander zu arbeiten.

- **Development (Dev):** Ist für die Programmierung, Weiterentwicklung und das Testen der Software verantwortlich.
- **Operations (Ops):** Ist für die Bereitstellung, den Betrieb, die Überwachung und die Verfügbarkeit der Software verantwortlich.

Der DevOps Lifecycle folgt einem **iterativen und kontinuierlichen Ablauf**. Das bedeutet, dass die einzelnen Phasen nicht nur einmal durchlaufen, sondern regelmässig wiederholt werden. Die Software wird in kleinen Schritten entwickelt, getestet, bereitgestellt und verbessert.

### Phasen des DevOps Lifecycle

| Phase      | Beschreibung                                                             |
| ---------- | ------------------------------------------------------------------------ |
| 1. Plan    | Anforderungen und Aufgaben planen und priorisieren.                      |
| 2. Code    | Funktionen entwickeln und den Code versionieren, beispielsweise mit Git. |
| 3. Build   | Den Code automatisiert bauen und ausführbare Artefakte erstellen.        |
| 4. Test    | Automatisierte und gegebenenfalls manuelle Tests durchführen.            |
| 5. Release | Eine geprüfte Softwareversion für die Veröffentlichung vorbereiten.      |
| 6. Deploy  | Die Software in einer Zielumgebung bereitstellen.                        |
| 7. Operate | Die Software betreiben und ihre Verfügbarkeit sicherstellen.             |
| 8. Monitor | Fehler, Performance und Systemzustand überwachen und Feedback sammeln.   |

Die Erkenntnisse aus dem Monitoring fliessen wieder in die Planung ein. Dadurch entsteht ein kontinuierlicher Kreislauf. Die genaue Einteilung der Phasen kann je nach DevOps-Modell variieren.

### Ziele des DevOps Lifecycle

- Schnellere und häufigere Bereitstellung neuer Funktionen.
- Automatisierung wiederkehrender Aufgaben durch CI/CD.
- Frühzeitiges Erkennen und Beheben von Fehlern.
- Höhere Zuverlässigkeit und kontinuierliche Verbesserung der Software.

**CI (Continuous Integration):** Codeänderungen werden regelmässig integriert und automatisiert geprüft.

**CD (Continuous Delivery / Continuous Deployment):** Softwareänderungen werden automatisiert für die Bereitstellung vorbereitet oder direkt produktiv bereitgestellt.

## 3. Unterschiede zwischen SDLC und DevOps Lifecycle

_Geschrieben von Ajna_

### Traditioneller Ansatz und DevOps im Vergleich

**Traditioneller Entwicklungsansatz (z. B. Wasserfallmodell):**

- Die einzelnen Phasen werden nacheinander durchlaufen.
- Entwicklung und IT-Betrieb arbeiten häufig getrennt voneinander.
- Die Software wird hauptsächlich nach der Entwicklung getestet.
- Neue Versionen werden in grösseren Zeitabständen veröffentlicht.
- Viele Aufgaben werden manuell durchgeführt.
- Nachträgliche Änderungen können aufwendig sein.

**DevOps:**

- Die einzelnen Phasen werden kontinuierlich wiederholt.
- Entwicklung und IT-Betrieb arbeiten eng zusammen.
- Die Software wird laufend getestet und überwacht.
- Neue Funktionen werden regelmässig in kleinen Schritten bereitgestellt.
- Wiederkehrende Aufgaben werden durch CI/CD automatisiert.
- Auf Fehler, Feedback und neue Anforderungen kann schneller reagiert werden.

Das Ziel von DevOps ist es, Software schneller und zuverlässiger bereitzustellen, den manuellen Aufwand zu reduzieren und die Software kontinuierlich zu verbessern.

**Merksatz:** Der SDLC beschreibt, welche Phasen eine Software während ihres Lebenszyklus durchläuft. DevOps beschreibt, wie Entwicklung und Betrieb diese Phasen gemeinsam, kontinuierlich und möglichst automatisiert umsetzen. DevOps ersetzt den SDLC nicht, sondern ergänzt ihn.

## 4. Was ist ein MVP und welche Bedeutung hat es im DevOps Lifecycle?

…

## Transfer in unser Projekt

…

## Quellen

Mehrere Quellen pro Thema.

- …

## KI-Nachweis

Steht im [KI-Nachweis](../Dokumentation/KI-Nachweis.md) (ein Dokument für alle Abgaben).
