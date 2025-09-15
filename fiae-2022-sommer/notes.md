# Entwicklung und Umsetzung von Algorithmen

## Inhaltsverzeichnis 

- [Äquivalenzklassen](#äquivalenzklassen)
- [Code Coverage](#code-coverage)
- [Schreibtischtest](#schreibtischtest)
- [Stored Procedures](#stored-procedures)
- [Trigger](#trigger)
- [Unit Tests](#unit-tests)
- [Aggregation](#aggregation)
- [Anforderungsanalyse](#anforderungsanalyse)
- [Change Management](#change-management)
- [Dokumentenorientierte Datenbank](#dokumentenorientierte-datenbank)
- [Englisch](#englisch)
- [Fremdvergabe](#fremdvergabe)
- [Klassendiagramm](#klassendiagramm)
- [OAuth](#oauth)
- [Observer](#observer)
- [Pseudocode](#pseudocode)
- [Sequenzdiagramm](#sequenzdiagramm)
- [Ticketsystem](#ticketsystem)
- [Vorgehensmodelle](#vorgehensmodelle)
- [Zertifikate](#zertifikate)

## Aktivitätsdiagramm

```bash
cat ./fiae-2021-winter/notes.md
```

## Äquivalenzklassen

- Äquivalenzklassen sind Mengen von Eingabewerten, die sich im Hinblick auf das zu testende Verhalten eines Programms gleich verhalten. Das bedeutet, dass alle Werte innerhalb einer Äquivalenzklasse vom Programm auf die gleiche Weise verarbeitet werden und daher für Testzwecke als gleichwertig betrachtet werden können.

- Durch die Bildung von Äquivalenzklassen kann die Anzahl der notwendigen Testfälle reduziert werden, da es genügt, für jede Klasse einen repräsentativen Wert zu testen. Dies ist besonders wichtig beim Black-Box-Testen, um effizient und systematisch Testfälle auszuwählen.

- **Beispiel:** Bei der Eingabe eines Alters in ein Formular könnten die Äquivalenzklassen z.B. „gültige Werte“ (z.B. 0-120), „negative Werte“ und „zu große Werte“ sein. Für jede Klasse wird ein Wert getestet, um Fehler zu finden.

- **Vorteile:** Weniger Testaufwand, systematische Abdeckung.
- **Nachteile:** Fehler außerhalb der definierten Klassen können übersehen werden.

- **Typische Anwendung:** Softwaretests, insbesondere Black-Box-Tests, um Eingabebereiche systematisch abzudecken.
- **Hinweis:** Die Auswahl der Klassen sollte sorgfältig erfolgen, um möglichst viele Fehlerquellen zu erfassen.

- **Praxis-Tipp:** Bei der Testfall-Erstellung empfiehlt es sich, auch Grenzwerte (Boundary Values) zu berücksichtigen, da hier häufig Fehler auftreten.
- **Grenzwerte:** Werte am Rand einer Äquivalenzklasse, z.B. 0 und 120 beim Alter.

## Code Coverage 

- **Code Coverage (Testabdeckung)** ist ein Maß dafür, wie viel Prozent des Quellcodes eines Programms durch automatisierte Tests ausgeführt werden. Es zeigt, welche Teile des Codes getestet wurden und welche nicht. Eine hohe Code Coverage bedeutet, dass viele Codebereiche durch Tests abgedeckt sind, was die Wahrscheinlichkeit von unentdeckten Fehlern reduziert. Typische Metriken sind z.B. die Abdeckung von Zeilen, Funktionen oder Bedingungen.

- **Beispiel:** Ein Test deckt 80% der Codezeilen ab, aber nur 50% der Bedingungen. Das zeigt, dass noch wichtige Fälle fehlen könnten.

- **Vorteile:** Gibt einen Überblick über die Testabdeckung, hilft bei der Qualitätssicherung.
- **Nachteile:** Hohe Coverage garantiert keine Fehlerfreiheit, da nicht alle Sonderfälle getestet werden.

- **Typische Tools:** z.B. JaCoCo (Java), Istanbul (JavaScript), Coverage.py (Python).
- **Hinweis:** Neben der Zeilenabdeckung ist auch die Abdeckung von Verzweigungen und Pfaden wichtig.

- **Praxis-Tipp:** Code Coverage sollte als Werkzeug zur Verbesserung der Testqualität genutzt werden, aber nicht als alleiniges Ziel. Wichtig ist, dass die Tests auch sinnvolle Fehlerfälle abdecken.
- **Grenzen:** Manche Codebereiche (z.B. Logging, Fehlerbehandlung) sind schwer zu testen und werden oft bewusst ausgeschlossen.

## SQL Commands 
```bash
cat ./fiae-2021-winter/notes.md
```
## Pseudocode 
```bash
cat ./fiae-2021-winter/notes.md
```
## Relationales Datenmodell
```bash
cat ./fiae-2021-winter/notes.md
```

## Schreibtischtest 

- **Ein Schreibtischtest** (auch: Dry Run) ist eine Methode, bei der ein Algorithmus oder Programm gedanklich Schritt für Schritt durchgegangen wird, ohne ihn tatsächlich auszuführen. Dabei werden die Werte von Variablen und der Ablauf notiert, um Fehler oder logische Probleme frühzeitig zu erkennen. Schreibtischtests helfen, die Funktionsweise eines Programms zu überprüfen und zu verstehen.

- In der Praxis wird der Schreibtischtest oft auf Blattpapier durchgeführt, wobei man prüft, ob die einzelnen Schritte und Werte logisch Sinn ergeben.

- **Beispiel:** Man schreibt die Werte von Variablen bei jedem Schritt eines Algorithmus auf und prüft, ob das Ergebnis wie erwartet ist.

- **Vorteile:** Einfach, keine Software nötig, hilft beim Verständnis.
- **Nachteile:** Kann bei komplexen Algorithmen unübersichtlich werden.

- **Typische Anwendung:** Prüfung von Algorithmen, Pseudocode oder kleinen Programmen vor der Implementierung.
- **Hinweis:** Besonders hilfreich beim Debuggen und bei der Fehlersuche.

- **Praxis-Tipp:** Schreibtischtests eignen sich auch gut für die Teamarbeit, indem mehrere Personen gemeinsam einen Algorithmus durchgehen und diskutieren.
- **Grenzen:** Bei sehr großen Programmen ist ein Schreibtischtest oft nicht praktikabel, hier helfen automatisierte Tests.


## Stored Procedures 

- **Stored Procedures** sind gespeicherte Programme oder Abläufe, die direkt in einer Datenbank hinterlegt werden. Sie bestehen meist aus einer Folge von SQL-Befehlen und können mit Parametern aufgerufen werden. Stored Procedures dienen dazu, wiederkehrende Aufgaben, komplexe Abfragen oder Datenmanipulationen effizient und sicher auf der Datenbank auszuführen. Sie verbessern die Performance und erleichtern die Wartung, da die Logik zentral in der Datenbank gespeichert ist.

- **Beispiel:** Eine Stored Procedure berechnet automatisch Rabatte beim Kaufabschluss.

- **Vorteile:** Schnelle Ausführung, Wiederverwendbarkeit, Sicherheit.
- **Nachteile:** Änderungen erfordern oft Datenbankzugriff, weniger flexibel als externe Logik.

- **Typische Anwendung:** Automatisierung von Geschäftslogik direkt in der Datenbank, z.B. für Buchungen, Abrechnungen oder Validierungen.
- **Hinweis:** Stored Procedures können die Sicherheit erhöhen, da sie direkt auf der Datenbank ausgeführt werden und weniger Angriffsfläche bieten.

- **Praxis-Tipp:** Bei komplexen Geschäftsprozessen können Stored Procedures die Performance deutlich verbessern, da weniger Daten zwischen Anwendung und Datenbank übertragen werden müssen.
- **Grenzen:** Die Wartung kann aufwändig sein, wenn viele Stored Procedures existieren und die Logik verteilt ist.


## Trigger

- **Ein Trigger** ist ein Mechanismus in einer Datenbank, der automatisch eine bestimmte Aktion ausführt, wenn ein definiertes Ereignis eintritt, z.B. beim Einfügen, Ändern oder Löschen von Daten in einer Tabelle. Trigger werden verwendet, um Datenintegrität sicherzustellen, automatische Prüfungen oder Berechnungen durchzuführen und Abläufe zu automatisieren, ohne dass der Benutzer aktiv eingreifen muss.

- **Beispiel:** Ein Trigger prüft beim Einfügen eines Datensatzes, ob ein Wert gültig ist, oder aktualisiert automatisch einen Zeitstempel.

- **Vorteile:** Automatisierung, Sicherstellung von Regeln.
- **Nachteile:** Fehlerhafte Trigger können schwer zu finden sein, Performance kann leiden.

- **Typische Anwendung:** Automatische Protokollierung von Änderungen, Validierung von Daten, Berechnung von Werten beim Einfügen oder Ändern.
- **Hinweis:** Trigger sollten sparsam und gezielt eingesetzt werden, um die Performance nicht zu beeinträchtigen.

- **Praxis-Tipp:** Trigger sind besonders nützlich für Auditing-Zwecke, z.B. um Änderungen an wichtigen Daten automatisch zu protokollieren.
- **Grenzen:** Zu viele Trigger können zu unerwarteten Wechselwirkungen und schwer nachvollziehbaren Fehlern führen.

## Unit Tests 
```bash
cat ./fiae-2021-winter/notes.md
```

# Planen eines Software Produkts

## Aggregation 
```bash
cat ./fiae-2021-winter/notes.md
```
## Anforderungsanalyse 

- Die Anforderungsanalyse ist ein wichtiger Schritt im Softwareentwicklungsprozess. Sie dient dazu, die Anforderungen und Erwartungen der Stakeholder (z.B. Auftraggeber, Nutzer) systematisch zu erfassen, zu dokumentieren und zu prüfen.
- Ziel ist es, ein gemeinsames Verständnis über die zu entwickelnde Software zu schaffen und Missverständnisse zu vermeiden.
- Die Ergebnisse der Anforderungsanalyse bilden die Grundlage für die weitere Planung, das Design und die Umsetzung des Projekts.
- Typische Methoden sind Interviews, Workshops, Fragebögen und die Analyse bestehender Systeme.

**Beispiel:** Bei der Entwicklung einer App werden die Anforderungen der Nutzer durch Interviews und Umfragen erfasst und dokumentiert.
**Vorteile:** Klare Zieldefinition, weniger Missverständnisse, bessere Planung.
**Nachteile:** Aufwand für die Erhebung und Abstimmung, Anforderungen können sich im Projektverlauf ändern.
**Praxis-Tipp:** Anforderungen sollten regelmäßig überprüft und bei Bedarf angepasst werden (sog. „Change Requests“).

## Change Management

- Change Management bezeichnet alle Maßnahmen und Prozesse, die notwendig sind, um Änderungen in einem Unternehmen oder Projekt systematisch zu planen, umzusetzen und zu kontrollieren.
- Im IT-Kontext geht es darum, Änderungen an Systemen, Software oder Prozessen so zu steuern, dass Risiken minimiert und die Qualität sichergestellt wird.
- Ziel ist es, die Auswirkungen von Änderungen transparent zu machen, die Beteiligten einzubeziehen und einen reibungslosen Übergang zu gewährleisten.
- Typische Schritte sind die Beantragung, Bewertung, Freigabe, Umsetzung und Dokumentation von Änderungen.

**Beispiel:** Ein Software-Update wird zunächst beantragt, dann getestet und nach Freigabe produktiv eingespielt. Alle Schritte werden dokumentiert.
**Vorteile:** Strukturierte Abläufe, weniger Fehler, bessere Nachvollziehbarkeit.
**Nachteile:** Bürokratie, längere Entscheidungswege.
**Praxis-Tipp:** Ein gutes Change Management bezieht alle relevanten Stakeholder ein und kommuniziert Änderungen frühzeitig.

## Dokumentenorientierte Datenbank

- Dokumentenorientiert bezieht sich meist auf dokumentenorientierte Datenbanken. Diese speichern Daten in Form von Dokumenten, oft im JSON- oder XML-Format.
- Im Gegensatz zu relationalen Datenbanken werden die Daten nicht in Tabellen, sondern als flexible, strukturierte Dokumente abgelegt.
- Dokumentenorientierte Datenbanken eignen sich besonders für Anwendungen, bei denen die Datenstruktur variabel ist oder sich häufig ändert, z.B. bei Webanwendungen oder Content-Management-Systemen.
- Bekannte Beispiele sind MongoDB und CouchDB.

**Beispiel:** In einer E-Commerce-Anwendung werden Produktdaten als JSON-Dokumente gespeichert, die je nach Produkt unterschiedliche Felder enthalten können.
**Vorteile:** Hohe Flexibilität, einfache Skalierbarkeit, schnelle Entwicklung.
**Nachteile:** Komplexere Abfragen, weniger strenge Datenintegrität als bei relationalen Datenbanken.
**Praxis-Tipp:** Dokumentenorientierte Datenbanken sind ideal für Projekte mit sich ändernden Anforderungen und variablen Datenstrukturen.

## Englisch

- Englisch: A relational database organizes data into tables, which consist of rows and columns. Each row represents a record, and each column represents a field within the record.
- Deutsch: Eine relationale Datenbank organisiert Daten in Tabellen, die aus Zeilen und Spalten bestehen. Jede Zeile stellt einen Datensatz dar und jede Spalte ein Feld innerhalb des Datensatzes.

**Weitere Begriffe:**
- Table = Tabelle
- Row = Zeile
- Column = Spalte
- Record = Datensatz
- Field = Feld
**Praxis-Tipp:** Viele IT-Fachbegriffe stammen aus dem Englischen und werden auch im Deutschen oft direkt verwendet. Ein gutes Verständnis der englischen Begriffe erleichtert das Arbeiten mit Dokumentationen und internationalen Teams.


## Fremdvergabe

- Fremdvergabe (Outsourcing) bezeichnet die Auslagerung von Aufgaben, Projekten oder Prozessen an externe Dienstleister oder Unternehmen. Ziel ist es, Ressourcen zu sparen, Kosten zu senken oder Zugang zu spezialisiertem Know-how zu erhalten. Bei der Fremdvergabe übernimmt der externe Partner die vereinbarten Leistungen, während das auftraggebende Unternehmen sich auf seine Kernkompetenzen konzentrieren kann. Typische Beispiele sind die Fremdvergabe von IT-Dienstleistungen, Softwareentwicklung oder Support.

**Vorteile:** Zugang zu Experten, Kostenersparnis, Flexibilität.
**Nachteile:** Abhängigkeit vom Dienstleister, weniger Kontrolle, Datenschutzrisiken.

**Typische Anwendung:** IT-Outsourcing, Cloud-Dienste, externe Entwicklungsteams, Support und Wartung.
**Hinweis:** Ein klarer Vertrag und regelmäßige Kontrolle sind wichtig, um die Qualität und Sicherheit der Fremdvergabe zu gewährleisten.

**Praxis-Tipp:** Fremdvergabe eignet sich besonders für Aufgaben, die nicht zum Kerngeschäft gehören oder für die intern keine Ressourcen vorhanden sind.
**Grenzen:** Die Kommunikation mit externen Partnern kann aufwändig sein, kulturelle und sprachliche Unterschiede sollten beachtet werden.

## Klassendiagramm

```bash
cat ./fiae-2021-winter/notes.md
```
## OAuth

- OAuth (Open Authorization) ist ein offenes Protokoll, das es ermöglicht, dass Anwendungen im Namen eines Nutzers auf dessen Daten bei einem anderen Dienst zugreifen können, ohne das Passwort weiterzugeben.
- Typischer Anwendungsfall: Login mit Google, Facebook oder anderen Diensten.
- Vorteile: Erhöhte Sicherheit, da keine Passwörter geteilt werden müssen.
- Nachteile: Komplexität bei der Implementierung.
- Praxis-Tipp: OAuth wird oft in Kombination mit OpenID Connect für Authentifizierung verwendet.
- Beispiel: Ein Nutzer meldet sich bei einer Drittanbieter-App mit seinem Google-Account an, ohne das Google-Passwort preiszugeben.
- Grenzen: Die korrekte Konfiguration ist wichtig, um Sicherheitslücken zu vermeiden.

## Observer

- Das Observer-Pattern (Beobachter-Muster) ist ein Entwurfsmuster, bei dem ein Objekt (Subject) mehrere andere Objekte (Observer) über Änderungen informiert.
- Typischer Anwendungsfall: GUI-Elemente, die sich bei Datenänderungen automatisch aktualisieren.
- Vorteile: Entkopplung von Komponenten, einfache Erweiterbarkeit.
- Nachteile: Kann zu vielen Benachrichtigungen und komplexen Abhängigkeiten führen.
- Praxis-Tipp: Das Observer-Muster ist besonders nützlich in Event-getriebenen Systemen und bei der Implementierung von Benachrichtigungen.
- Beispiel: In einer Chat-App werden alle Teilnehmer benachrichtigt, wenn eine neue Nachricht eingeht.
- Grenzen: Bei sehr vielen Observern kann die Performance leiden.

## Pseudocode

```bash
cat ./fiae-2021-winter/notes.md
```

## Sequenzdiagramm

- Ein Sequenzdiagramm ist eine UML-Darstellung, die den zeitlichen Ablauf von Nachrichten und Interaktionen zwischen Objekten oder Komponenten zeigt.
- Typischer Anwendungsfall: Visualisierung von Abläufen in Software, z.B. bei der Anmeldung eines Nutzers.
- Vorteile: Übersichtliche Darstellung komplexer Abläufe.
- Nachteile: Kann bei großen Systemen schnell unübersichtlich werden.
- Praxis-Tipp: Sequenzdiagramme helfen, Schnittstellen und Kommunikationswege zwischen Komponenten zu klären.
- Beispiel: Darstellung des Anmeldeprozesses eines Nutzers mit Interaktion zwischen Frontend, Backend und Datenbank.
- Grenzen: Für sehr komplexe Abläufe sind andere Diagrammtypen (z.B. Aktivitätsdiagramme) oft besser geeignet.

<img src="./sequenzdiagramm.png">

## Ticketsystem

- Ein Ticketsystem ist eine Software zur Verwaltung und Nachverfolgung von Aufgaben, Anfragen oder Problemen (Tickets) in Unternehmen oder Projekten.
- Typischer Anwendungsfall: IT-Support, Helpdesk, Projektmanagement.
- Vorteile: Strukturierte Bearbeitung, bessere Nachvollziehbarkeit, Priorisierung von Aufgaben.
- Nachteile: Kann bei schlechter Pflege unübersichtlich werden.
- Praxis-Tipp: Ticketsysteme wie Jira, OTRS oder Redmine sind weit verbreitet und unterstützen die Zusammenarbeit im Team.
- Beispiel: Ein IT-Support-Team bearbeitet eingehende Störungsmeldungen und dokumentiert die Lösung im Ticket.
- Grenzen: Die Akzeptanz im Team ist wichtig, sonst werden Tickets nicht konsequent gepflegt.

## Vorgehensmodelle

```bash
cat ./fiae-2021-winter/notes.md
```

## Zertifikate

```bash
cat ./fiae-2021-winter/notes.md
```
