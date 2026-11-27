# T1 – DevOps-Kultur: CALMS und The Three Ways

_Bearbeitet von: Leon (Culture, Automation), Levin (Lean), Rana (Measurement, Sharing), Leart (The Three Ways), Claude/KI (Teil 3–5) · Abgabe: Woche 2 (FG1)_

> Teil 1 und 2 wurden von Hand geschrieben. Grammatik und Satzstellung hat danach Claude (KI) überarbeitet.
> **Teil 3 bis 5 hat Claude (KI) geschrieben**, auf Grundlage unserer Teile 1 und 2, der Unterlagen und der Fallstudie. Bei jedem Abschnitt steht, wer ihn geschrieben hat.

## 1. Verständnis CALMS

### Culture

_Geschrieben von Leon_

Culture meint die Kultur in der Firma und im Team. Es heisst nicht: Unser Team hat das Feature programmiert, wir sind fertig, den Rest schieben wir ab, und der Betrieb muss schauen, wie es ohne Fehler beim Kunden landet. Stattdessen arbeiten alle zusammen. Es gibt zwar weiterhin Teams, aber der Übergang zwischen ihnen muss stimmen. Man hilft einander, stimmt sich in Meetings ab und klärt, wie es weitergeht, damit man gemeinsam ans Ziel kommt. Dazu gehört, dass Fehler erlaubt sind. Wenn ein Problem auftaucht, reagiert das ganze Team darauf. Kurz gesagt: Teamarbeit fördern und alles aus dem Weg räumen, was sie verhindert.

Das gilt auch für das Management. Es muss Fehler ebenfalls erlauben und dann mithelfen, einen Weg zu finden, um sie zu beheben. Es muss auch einmal akzeptieren können, dass etwas länger braucht als geplant, und dann gemeinsam mit dem Team überlegen, was man machen kann, zum Beispiel die Arbeit aufteilen.

Culture ist das Fundament, weil das beste Tool nichts bringt, wenn die Zusammenarbeit beim Programmieren, Testen, Reviewen und Releasen nicht funktioniert, und zwar über alle Ebenen, zum Beispiel Frontend und Backend. Entscheidend ist am Ende nur, dass ein Feature möglichst schnell und ohne Fehler beim Kunden landet.

**Bei TechNova:** Vorher war die Struktur schlecht. Ich denke, viele wussten gar nicht, wie die Arbeit ausserhalb ihrer Abteilung funktioniert. Bei Fehlern haben sie sich gegenseitig die Schuld zugeschoben, und am Schluss musste wahrscheinlich jemand alles zusammentragen, damit überhaupt ein Release möglich war. Mit Workshops und Teambuilding wurde die Zusammenarbeit gestärkt. Über das Wiki werden Informationen geteilt, sodass bei Fragen jede Person zuerst selbst nachschauen kann. Durch die bessere Zusammenarbeit und Abstimmung spart TechNova heute viel Zeit.

### Automation

_Geschrieben von Leon_

Bei DevOps werden viele Schritte automatisiert, vor allem mit CI/CD-Pipelines. Dafür braucht es Unit-Tests. Die Pipeline führt sie automatisch aus und prüft so, ob das Feature ohne Fehler im Code funktioniert. Auch das Deployment wird automatisiert, was zusätzlich Zeit spart: Es muss nur noch der Pull Request reviewt werden, und dann wird released. Durch das Monitoring nach dem Deployment werden Fehler früh gefunden, die man sonst erst bemerkt, wenn sich der Kunde meldet.

Das Aussehen muss trotzdem noch von Hand angeschaut werden. Tests zeigen nur, ob der Code funktioniert, nicht, ob wir das Ziel des Kunden erreicht haben.

Eine Pipeline allein ist aber noch kein DevOps. Wenn die Kultur trotz Automatisierung gleich bleibt, kann es passieren, dass auch Fehler automatisiert werden. Diese findet man dann nie, weil niemand mehr von Hand nachschaut, was automatisch läuft.

**Bei TechNova:** Hier sieht man einen klaren Vorher-Nachher-Effekt. Vorher wurde viel Zeit ins manuelle Testen und ins Debugging gesteckt. Jetzt läuft das automatisch, und man verhindert viele Fehler, die beim manuellen Testen passieren, zum Beispiel weil man etwas vergessen hat. Durch die gesparte Zeit kann TechNova jetzt wöchentlich releasen statt nur halbjährlich. Manuelles Testen am Schluss bleibt aber wichtig.

### Lean

_Geschrieben von Levin_

Bei Lean geht es darum, unnötige Arbeit zu vermeiden und die Arbeitsweise laufend zu verbessern. Ursprünglich kommt dieses Prinzip von Toyota, wird aber heutzutage auch in der Softwareentwicklung eingesetzt.

**Bei TechNova:** Früher dauerte es sechs Monate oder sogar länger, bis neue Funktionen veröffentlicht wurden. Dadurch entstanden lange Wartezeiten, die im Lean-Management als Waste bezeichnet werden. Zudem wurden viele Tests und Deployments manuell durchgeführt, was viel Zeit kostete. Durch den Einsatz von Kanban und einer CI/CD-Pipeline konnten sie diesen Aufwand reduzieren, wöchentlich neue Releases veröffentlichen und schneller auf Kundenfeedback reagieren.

**In unserem Projekt:** Wir arbeiten auch mit einem Kanban-Board und wöchentlichen Sprints. Was wir aber noch verbessern könnten, sind unsere Wartezeiten. Zum Beispiel wartet unser Pull Request #31 schon seit zwei Wochen auf einen Review. Um solche Wartezeiten in Zukunft zu vermeiden, könnten wir im Team eine Regel festlegen, dass Pull Requests innerhalb von zwei Arbeitstagen überprüft werden. Dadurch würde bereits erledigte Arbeit nicht unnötig liegen bleiben.

### Measurement

_Geschrieben von Rana_

Bei Measurement geht es darum, Arbeitsprozesse zu messen und anhand der Ergebnisse zu verbessern. Dadurch kann ein Unternehmen erkennen, wo Probleme bestehen und welche Abläufe optimiert werden müssen.

**Bei TechNova:** TechNova verwendete dafür folgende Kennzahlen:

- **Deployment-Frequenz:** Wie oft neue Softwareversionen veröffentlicht werden.
- **Lead Time:** Wie lange es dauert, bis eine Änderung bereitgestellt wird.
- **MTTR (Mean Time to Recovery):** Durchschnittliche Zeit, bis ein System nach einer Störung wieder funktioniert.

Durch diese Messungen konnte TechNova den Fortschritt der DevOps-Transformation überprüfen und Verbesserungspotenzial erkennen.

### Sharing

_Geschrieben von Rana_

Bei Sharing geht es darum, Wissen und Erfahrungen innerhalb des Unternehmens auszutauschen. Dadurch können Mitarbeitende voneinander lernen, Probleme gemeinsam lösen und vermeiden, dass dieselben Fehler wiederholt werden.

**Bei TechNova:** TechNova förderte den Wissensaustausch durch ein internes Wiki, Lernveranstaltungen und Erfahrungsberichte. Dadurch wurde die Zusammenarbeit zwischen den Abteilungen verbessert, und das Wissen war für mehr Mitarbeitende zugänglich.

## 2. Verständnis The Three Ways

_Geschrieben von Leart_

Die Three Ways zeigen, wie eine Änderung möglichst schnell und sauber vom Entwickler zum Kunden kommt und was danach passiert.

### First Way – Systems Thinking (Flow)

Beim Flow geht es darum, dass Arbeit ohne Stopp durch den ganzen Prozess läuft. Eine Änderung soll nicht irgendwo liegen und auf jemanden warten. Jede Übergabe (Entwicklung, Test, Betrieb) und jede Freigabe kostet Zeit, also versucht man, davon so wenige wie möglich zu haben.

Dafür macht man zum Beispiel Folgendes:

- Änderungen klein halten, dann sind sie schneller fertig und einfacher zu testen.
- Die Arbeit sichtbar machen, etwa mit einem Kanban-Board.
- WIP-Limits setzen, also eine Obergrenze, wie viele Aufgaben gleichzeitig laufen dürfen.
- Unnötige Freigaben und Übergaben streichen.
- Wiederkehrendes automatisieren, zum Beispiel Deployments.

Am Ende will man einen schnellen, stabilen Weg zum Kunden und Engpässe früh erkennen.

### Second Way – Feedback Loops

Hier geht es darum, möglichst schnell zu merken, ob etwas funktioniert. Rückmeldungen aus dem Betrieb und von den Kunden sollen schnell beim Team ankommen. Je früher man einen Fehler findet, desto weniger kostet es, ihn zu beheben.

Dafür macht man zum Beispiel Folgendes:

- Oft deployen, damit regelmässig Rückmeldungen kommen.
- Automatisierte Tests auf mehreren Ebenen (Unit, Integration, System, Akzeptanz).
- Code Reviews durch andere.
- Technische Schulden abbauen.

Beispiel: Ein Unit-Test schlägt beim Programmieren fehl, ich korrigiere es sofort, und der Kunde merkt gar nichts davon.

### Third Way – Continual Learning and Experimentation

Das ist eher eine Frage der Haltung im Team. Fehler werden nicht versteckt, sondern offen angeschaut, damit man daraus lernt. Wenn etwas ausfällt, fragt man nach der Ursache und nicht nach dem Schuldigen. Danach teilt man die Erkenntnisse, damit andere Teams nicht denselben Fehler machen.

Dazu gehört auch, Neues auszuprobieren. Kontrollierte Experimente funktionieren aber nur, wenn die Führung dahintersteht.

### Wie hängen die drei zusammen?

- Flow sorgt dafür, dass Änderungen schnell ausgeliefert werden.
- Feedback zeigt, ob das Ergebnis stimmt.
- Lernen verbessert den Prozess danach Schritt für Schritt.

CI und CD (T3 und T4) sind die wichtigsten Werkzeuge, um alle drei Wege in der Praxis umzusetzen.

### Bezug zu TechNova

Die Fallstudie sagt nicht, welche Massnahme welches Ergebnis gebracht hat. Die Zuordnung ist also meine Einschätzung.

**Flow**
- Problem: Entwicklung, Test und Betrieb arbeiteten isoliert, und viele Schritte liefen manuell. Features kamen dadurch erst nach sechs Monaten oder später auf den Markt.
- Massnahme: Die CI/CD-Pipeline automatisiert Tests und Deployments, und die Kanban-Boards machen die Arbeit sichtbar.
- Wirkung: Es gibt weniger manuelle Schritte und Übergaben, und Engpässe fallen früher auf. Das Ergebnis sind wöchentliche statt halbjährliche Releases.

**Feedback**
- Problem: Kundenrückmeldungen wurden nicht schnell genug umgesetzt, und die Qualität litt unter der Trennung von Dev und Ops.
- Massnahme: Mit der Pipeline kann man viel häufiger releasen. Die Metriken (Deployment-Frequenz, Lead Time, MTTR) zeigen, wie gut der Prozess läuft. MTTR ist die durchschnittliche Zeit, bis ein Fehler im Betrieb behoben ist.
- Wirkung: Rückmeldungen kommen früher zurück, und Fehler fallen früher auf. Deshalb ist die Kundenzufriedenheit gestiegen.

**Kontinuierliches Lernen**
- Problem: die Silos und die Schuldzuweisungen bei Fehlern.
- Massnahme: Workshops, Teambuilding, Wiki, interne Lernformate und Erfahrungsberichte bringen die Teams zusammen und verteilen Wissen.
- Wirkung: Wer keine Schuldigen sucht, arbeitet besser zusammen. Darum wurde die Zusammenarbeit zwischen Entwicklung und Betrieb stabiler.

Flow brachte das Tempo, Feedback zeigte, ob die Kunden zufrieden sind, und das Lernen hielt die Zusammenarbeit stabil. Ohne die Kulturmassnahmen wäre die Pipeline vermutlich nur ein Tool geblieben. Das passt auch zu CALMS, wo Automation allein ohne Culture nicht reicht.

## 3. Vergleich

| Gemeinsame Idee | CALMS-Bezug | Bezug zu The Three Ways | Beispiel aus der Fallstudie | Eigene Einschätzung |
|-----------------|-------------|-------------------------|-----------------------------|---------------------|
| Zusammen statt gegeneinander | Culture | First Way: aufs Ganze schauen, nicht nur aufs eigene Team | Vorher Silos, danach Workshops und Teambuilding | Das ist die Basis. Ohne das bringt kein Tool etwas. |
| Arbeit soll nicht liegen bleiben | Automation, Lean | First Way: Flow | Pipeline und Kanban, Releases jede Woche statt alle sechs Monate | Der grösste sichtbare Erfolg. |
| Schnell merken, ob es klappt | Measurement | Second Way: Feedback | Sie messen Deployment-Frequenz, Lead Time und MTTR | Zahlen bringen nur etwas, wenn man danach auch handelt. |
| Aus Fehlern lernen | Culture, Sharing | Third Way: Lernen | Vorher Schuldzuweisungen, danach Wiki und Erfahrungsberichte | Dauert am längsten, hält aber am längsten. |
| Immer ein bisschen besser werden | Lean | Third Way: Experimentieren | Die Umstellung dauerte 18 Monate, Schritt für Schritt | DevOps ist nie richtig „fertig“. |

**Der grösste Unterschied:** CALMS ist wie eine Checkliste. Sie zeigt, welche Bereiche eine Firma braucht. Die Three Ways zeigen dagegen den Weg der Arbeit: zuerst zum Kunden, dann die Rückmeldung zurück, dann daraus lernen. Messen und Teilen sind bei CALMS eigene Punkte. Bei den Three Ways stecken sie im Feedback und im Lernen drin.

## 4. Bewertung der Transformation (Fallstudie TechNova Solutions)


Am meisten gebracht haben unserer Meinung nach diese zwei Dinge:

**1. Die CI/CD-Pipeline**
Hier sieht man den Erfolg direkt: Releases jede Woche statt alle sechs Monate. Bei CALMS ist das Automation, weil das Testen und Deployen von Hand wegfällt. Bei den Three Ways hilft die Pipeline beim Flow, weil Änderungen nicht mehr warten müssen. Und sie hilft beim Feedback, weil jede Änderung automatisch getestet wird.

**2. Die Kulturmassnahmen: Workshops, Teambuilding und Wissensaustausch**
Das sieht man in keiner Zahl, aber ohne das hätte die Pipeline wenig gebracht. Bei CALMS ist das Culture und Sharing. Die Teams reden wieder miteinander, und Wissen ist nicht mehr bei einzelnen Personen versteckt. Bei den Three Ways ist das der Third Way: Wer keine Schuldigen sucht, spricht offen über Fehler. Erst dann traut man sich, jede Woche zu releasen.

**Warum diese zwei?** Sie gehören zusammen. Die Pipeline macht schnell, die Kultur sorgt dafür, dass man das auch nutzt. In der CALMS-Unterlage steht sinngemäss: Wer nur automatisiert, automatisiert auch seine Fehler.

## 5. Transfer


**Beispiel: unser eigenes Team im Projekt „Band und Alben“**

Wir sind fünf Leute, arbeiten in Sprints von einer Woche, mit Kanban-Board, Branches und Pull Requests.

**Was bei uns am meisten besser werden muss:**

- **Bei CALMS: Lean.** Bei uns bleibt Arbeit liegen. Pull Request #31 wartet seit zwei Wochen auf ein Review. Dazu haben wir Vorlagen gemacht, die noch niemand braucht. Beides ist Verschwendung.
- **Bei den Three Ways: der First Way (Flow).** Unsere Arbeit staut sich beim Review. Am Ende des Tages sammeln wir ausserdem alles bei einer Person. So wird diese Person zum Flaschenhals.

**Was wir ändern könnten:**

- Reviews innerhalb eines Tages machen
- kleinere Pull Requests, dann geht das Review schneller
- jede Person macht ihren eigenen Pull Request
- Vorlagen erst machen, wenn wir sie brauchen

> Hinweis: Der Auftrag erlaubt auch ein Beispiel aus dem eigenen Betrieb. Das wäre persönlicher.

## Quellen

- CALMS: https://ch-tbz-it.gitlab.io/Stud/m324/Kultur/CALMS/
- The Three Ways: https://ch-tbz-it.gitlab.io/Stud/m324/Kultur/TheThreeWays/

## KI-Nachweis

Steht im [KI-Nachweis](../Dokumentation/KI-Nachweis.md#t1--devops-kultur).
