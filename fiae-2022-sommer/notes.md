# Entwicklung und Umsetzung von Algorithmen

## Inhaltsverzeichnis 

- [Äquivalenzklassen](#äquivalenzklassen)
- [Code Coverage](#code-coverage)
- [Schreibtischtest](#schreibtischtest)
- [Stored Procedures](#stored-procedures)
- [Trigger](#trigger)

## Aktivitätsdiagramm

```bash
cat ./fiae-2021-winter/notes.md
```

## Äquivalenzklassen

Äquivalenzklassen sind Mengen von Eingabewerten, die sich im Hinblick auf das zu testende Verhalten eines Programms gleich verhalten. Das bedeutet, dass alle Werte innerhalb einer Äquivalenzklasse vom Programm auf die gleiche Weise verarbeitet werden und daher für Testzwecke als gleichwertig betrachtet werden können.

Durch die Bildung von Äquivalenzklassen kann die Anzahl der notwendigen Testfälle reduziert werden, da es genügt, für jede Klasse einen repräsentativen Wert zu testen. Dies ist besonders wichtig beim Black-Box-Testen, um effizient und systematisch Testfälle auszuwählen.

## Code Coverage 

Code Coverage (Testabdeckung) ist ein Maß dafür, wie viel Prozent des Quellcodes eines Programms durch automatisierte Tests ausgeführt werden. Es zeigt, welche Teile des Codes getestet wurden und welche nicht. Eine hohe Code Coverage bedeutet, dass viele Codebereiche durch Tests abgedeckt sind, was die Wahrscheinlichkeit von unentdeckten Fehlern reduziert. Typische Metriken sind z.B. die Abdeckung von Zeilen, Funktionen oder Bedingungen.

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

Ein Schreibtischtest (auch: Dry Run) ist eine Methode, bei der ein Algorithmus oder Programm gedanklich Schritt für Schritt durchgegangen wird, ohne ihn tatsächlich auszuführen. Dabei werden die Werte von Variablen und der Ablauf notiert, um Fehler oder logische Probleme frühzeitig zu erkennen. Schreibtischtests helfen, die Funktionsweise eines Programms zu überprüfen und zu verstehen.

In der Praxis wird der Schreibtischtest oft auf Blattpapier durchgeführt, wobei man prüft, ob die einzelnen Schritte und Werte logisch Sinn ergeben.


## Stored Procedures 

Stored Procedures sind gespeicherte Programme oder Abläufe, die direkt in einer Datenbank hinterlegt werden. Sie bestehen meist aus einer Folge von SQL-Befehlen und können mit Parametern aufgerufen werden. Stored Procedures dienen dazu, wiederkehrende Aufgaben, komplexe Abfragen oder Datenmanipulationen effizient und sicher auf der Datenbank auszuführen. Sie verbessern die Performance und erleichtern die Wartung, da die Logik zentral in der Datenbank gespeichert ist.


## Trigger

Ein Trigger ist ein Mechanismus in einer Datenbank, der automatisch eine bestimmte Aktion ausführt, wenn ein definiertes Ereignis eintritt, z.B. beim Einfügen, Ändern oder Löschen von Daten in einer Tabelle. Trigger werden verwendet, um Datenintegrität sicherzustellen, automatische Prüfungen oder Berechnungen durchzuführen und Abläufe zu automatisieren, ohne dass der Benutzer aktiv eingreifen muss.

## Unit Tests 
```bash
cat ./fiae-2021-winter/notes.md
```

