# Entwicklung und Umsetzung von Algorithmen

## Inhaltsverzeichnis

- [Dateigrößen berechnen](#dateigrößenberechnen)
- [Pseudocode](#pseudocode)
- [Relationales Datenmodell](#relationalesdatenmodell)
- [Sequenzdiagramm](#sequenzdiagramm)
- [SQL](#sql)

# Planen eines Softwareproduktes

## Inhaltsverzeichnis

- [Aktivitätsdiagramm](#aktivitätsdiagramm)
- [Dokumentenorientierte Datenbank](#dokumentenorientiertedatenbank)
- [ERM](#erm)
- [Green IT](#greenit)
- [JSON](#json)
- [KI](#ki)
- [Mockups](#mockups)
- [Stakeholder](#stakeholder)
- [Testkonzept](#testkonzept)
- [Transaktionen](#transaktionen)
- [UI-Design](#ui-design)
- [User-Stories](#user-stories)
- [Workshop](#workshop)

## Dateigrößenberechnen

Um die Größe einer Datei zu berechnen, muss man wissen, wie viele Informationen (Bits/Bytes) gespeichert werden und wie die Daten strukturiert sind. Die wichtigsten Einheiten sind:

- **1 Bit** = kleinste Informationseinheit (0 oder 1)
- **1 Byte** = 8 Bit

Größeneinheiten:
- **1 Kilobyte (KB)** = 1024 Byte (2 ^ 10)
- **1 Megabyte (MB)** = 1024 KB = 1.048.576 Byte (2 ^ 20)
- **1 Gigabyte (GB)** = 1024 MB = 1.073.741.824 Byte (2 ^ 30)

**Beispiel:**
Eine Textdatei mit 1000 Zeichen (ASCII, 1 Byte pro Zeichen):

```
1000 Zeichen × 1 Byte = 1000 Byte ≈ 0,98 KB
```

**Bilddatei (unkomprimiert, z.B. BMP):**
Ein Bild mit 800×600 Pixeln, 24 Bit Farbtiefe (3 Byte pro Pixel):

```
800 × 600 × 3 Byte = 1.440.000 Byte ≈ 1,37 MB
```

**Formel allgemein:**
```
Dateigröße = Anzahl der Elemente × Größe pro Element
```

**Hinweis:** Komprimierte Formate (z.B. JPG, ZIP) benötigen meist weniger Speicherplatz, da sie Daten effizienter speichern.

## Pseudocode

```bash
cat ./fiae-2021-winter/notes.md
```

## Relationales Datenmodell 

```bash
cat ./fiae-2021-winter/notes.md
```

## Sequenzdiagramm

```bash
cat ./fiae-2022-sommer/notes.md
```

## SQL

```bash
cat ./fiae-2021-winter/notes.md
```

## Aktivitätsdiagramm

```bash
cat ./fiae-2021-winter/notes.md
```

## Dokumentenorientierte Datenbank

```bash
cat ./fiae-2022-sommer/notes.md
```

## ERM 

```bash
cat ./fiae-2021-winter/notes.md
```

## Green IT 

Green IT (auch "grüne Informationstechnologie") bezeichnet Maßnahmen und Konzepte, um die Umweltauswirkungen der IT zu minimieren. Ziel ist es, den Energieverbrauch und Ressourcenbedarf während des gesamten Lebenszyklus von IT-Systemen zu reduzieren.

**Wichtige Aspekte von Green IT:**
- **Energieeffiziente Hardware:** Auswahl von Geräten mit geringem Stromverbrauch (z.B. Energy Star-Zertifizierung).
- **Virtualisierung:** Mehrere virtuelle Server auf einer physischen Maschine reduzieren den Hardwarebedarf.
- **Cloud Computing:** Zentrale Rechenzentren können effizienter betrieben werden als viele kleine Server.
- **Recycling und Entsorgung:** Fachgerechte Entsorgung und Wiederverwertung von Altgeräten.
- **Softwareoptimierung:** Programme so entwickeln, dass sie möglichst wenig Ressourcen benötigen.
- **Nutzung erneuerbarer Energien:** Einsatz von Ökostrom in Rechenzentren und Büros.

**Vorteile:**
- Senkung der Betriebskosten durch geringeren Energieverbrauch
- Beitrag zum Umweltschutz und zur Nachhaltigkeit
- Verbesserung des Unternehmensimages

**Beispielmaßnahmen:**
- Einsatz von Energiesparmodi bei Computern und Monitoren
- Serverkonsolidierung durch Virtualisierung
- Papierloses Büro durch digitale Prozesse

## JSON 

JSON steht für **JavaScript Object Notation** und ist ein kompaktes, textbasiertes Datenformat zum Austausch von Daten zwischen Systemen. Es ist leicht lesbar und wird häufig für die Übertragung von Daten zwischen Webanwendungen und Servern verwendet.

**Eigenschaften:**
- Besteht aus Schlüssel-Wert-Paaren
- Unterstützt verschachtelte Strukturen (Objekte und Arrays)
- Plattformunabhängig und sprachübergreifend nutzbar

**Beispiel:**
```json
{
  "name": "Max Mustermann",
  "alter": 25,
  "istStudent": true,
  "faecher": ["Mathematik", "Informatik"],
  "adresse": {
    "stadt": "Berlin",
    "plz": "10115"
  }
}
```

**Vorteile:**
- Einfach zu lesen und zu schreiben
- Von vielen Programmiersprachen unterstützt
- Ideal für Web-APIs und Konfigurationsdateien

**Hinweis:** JSON unterstützt keine Kommentare und keine Datentypen wie Datum oder Binärdaten direkt.

## KI 

KI steht für **Künstliche Intelligenz** und bezeichnet Systeme oder Programme, die Aufgaben ausführen können, die normalerweise menschliche Intelligenz erfordern. Dazu gehören z.B. das Erkennen von Sprache und Bildern, das Treffen von Entscheidungen oder das Lernen aus Erfahrungen.

**Arten von KI:**
- **Schwache KI:** Löst spezifische Aufgaben (z.B. Sprachassistenten, Schachprogramme).
- **Starke KI:** Könnte eigenständig denken und handeln wie ein Mensch (existiert bisher nicht).

**Anwendungsgebiete:**
- Spracherkennung (z.B. Siri, Alexa)
- Bilderkennung (z.B. automatische Tagging in Fotos)
- Empfehlungssysteme (z.B. Netflix, Amazon)
- Autonomes Fahren
- Medizinische Diagnostik

**Technologien und Methoden:**
- **Maschinelles Lernen:** Algorithmen lernen aus Daten, Muster zu erkennen.
- **Neuronale Netze:** Inspiriert vom menschlichen Gehirn, besonders für komplexe Aufgaben wie Bild- und Spracherkennung.
- **Deep Learning:** Tiefe neuronale Netze für besonders große und komplexe Datenmengen.

**Vorteile:**
- Automatisierung von Routineaufgaben
- Verarbeitung großer Datenmengen
- Unterstützung bei komplexen Entscheidungen

**Herausforderungen:**
- Datenschutz und Ethik
- Erklärbarkeit von Entscheidungen
- Abhängigkeit von Datenqualität

## Mockups

Mockups sind visuelle Entwürfe von Benutzeroberflächen, die das Aussehen und die Anordnung von Elementen einer Anwendung oder Website zeigen. Sie dienen dazu, Designideen zu veranschaulichen und mit Stakeholdern abzustimmen, bevor die eigentliche Entwicklung beginnt.

**Eigenschaften von Mockups:**
- Zeigen Farben, Schriftarten, Layout und grafische Elemente
- Sind meist statisch (keine Interaktivität)
- Detaillierter als Wireframes, aber weniger funktional als Prototypen

**Vorteile:**
- Frühes Feedback von Nutzern und Auftraggebern möglich
- Missverständnisse im Designprozess werden reduziert
- Änderungen sind in dieser Phase noch einfach und kostengünstig

**Tools für Mockups:**
- Figma
- Adobe XD
- Sketch
- Balsamiq

**Beispielanwendung:**
Vor der Entwicklung einer App wird ein Mockup erstellt, um das Design mit dem Kunden abzustimmen und die Benutzerführung zu optimieren.

## Stakeholder 

Stakeholder sind alle Personen, Gruppen oder Organisationen, die ein Interesse am Verlauf oder Ergebnis eines Projekts haben oder davon betroffen sind. Sie können sowohl innerhalb als auch außerhalb eines Unternehmens stehen.

**Beispiele für Stakeholder:**
- Auftraggeber/Kunde
- Endnutzer/Anwender
- Projektteam/Entwickler
- Management/Führungskräfte
- Lieferanten und Partner
- Gesetzgeber und Behörden

**Bedeutung im Projekt:**
- Stakeholder haben unterschiedliche Erwartungen, Anforderungen und Einflussmöglichkeiten.
- Eine frühzeitige Identifikation und Einbindung der Stakeholder ist wichtig für den Projekterfolg.
- Durch regelmäßige Kommunikation können Missverständnisse und Widerstände vermieden werden.

**Stakeholder-Analyse:**
- Identifikation aller relevanten Stakeholder
- Analyse ihrer Interessen, Erwartungen und ihres Einflusses
- Entwicklung einer Kommunikationsstrategie für den Umgang mit den Stakeholdern

## Testkonzept

Ein Testkonzept beschreibt die Strategie und die Vorgehensweise zur Qualitätssicherung eines Softwareprojekts. Es legt fest, wie, wann und womit getestet wird, um Fehler frühzeitig zu erkennen und die Anforderungen zu überprüfen.

**Inhalte eines Testkonzepts:**
- **Testziele:** Was soll durch die Tests erreicht werden?
- **Testarten:** z.B. Unit-Test, Integrationstest, Systemtest, Abnahmetest
- **Testobjekte:** Welche Komponenten oder Funktionen werden getestet?
- **Testmethoden:** Manuelle oder automatisierte Tests, Black-Box- oder White-Box-Testing
- **Testumgebung:** Hardware, Software, Testdaten, Tools
- **Testablauf:** Zeitplan, Reihenfolge der Tests, Verantwortlichkeiten
- **Fehlerdokumentation:** Wie werden Fehler erfasst und nachverfolgt?
- **Abnahmekriterien:** Wann gilt ein Test als bestanden?

**Vorteile eines Testkonzepts:**
- Klare Struktur und Transparenz im Testprozess
- Reduzierung von Fehlern und Risiken
- Nachvollziehbarkeit und Wiederholbarkeit der Tests

**Beispiel für Testarten:**
- **Unit-Test:** Test einzelner Programmfunktionen
- **Integrationstest:** Zusammenspiel mehrerer Komponenten
- **Systemtest:** Gesamtsystem unter realistischen Bedingungen
- **Abnahmetest:** Prüfung durch den Auftraggeber/Kunden

## Transaktionen 

Transaktionen sind in der Informatik eine Folge von Operationen, die als eine logische Einheit betrachtet werden. Besonders in Datenbanksystemen sorgen Transaktionen dafür, dass Daten konsistent und zuverlässig verarbeitet werden.

**Eigenschaften von Transaktionen (ACID-Prinzip):**
- **Atomicity (Atomarität):** Eine Transaktion wird ganz oder gar nicht ausgeführt.
- **Consistency (Konsistenz):** Nach einer Transaktion befindet sich die Datenbank in einem konsistenten Zustand.
- **Isolation (Isolation):** Gleichzeitige Transaktionen beeinflussen sich nicht gegenseitig.
- **Durability (Dauerhaftigkeit):** Nach Abschluss einer Transaktion bleiben die Änderungen dauerhaft erhalten, auch bei Systemausfällen.

**Beispiel:**  
Überweisung von Geld zwischen zwei Konten:
1. Betrag vom Konto A abbuchen
2. Betrag auf Konto B gutschreiben  
Beide Schritte müssen zusammen ausgeführt werden – schlägt einer fehl, wird alles zurückgesetzt (Rollback).

**Transaktionssteuerung in SQL:**
- `BEGIN TRANSACTION` – Startet eine Transaktion
- `COMMIT` – Bestätigt die Transaktion (Änderungen werden übernommen)
- `ROLLBACK` – Bricht die Transaktion ab (Änderungen werden rückgängig gemacht)

**Vorteile:**
- Schutz vor Datenverlust und Inkonsistenzen
- Ermöglicht parallele und sichere Verarbeitung von Daten

## UI-Design

```bash
cat ./fiae-2022-winter/notes.md
```

## User-Stories

User-Stories sind kurze, verständliche Beschreibungen von Anforderungen aus Sicht der Nutzer. Sie werden vor allem in agilen Projekten (z.B. Scrum) verwendet, um die gewünschten Funktionen einer Software zu erfassen.

**Aufbau einer User-Story:**
> Als [Rolle] möchte ich [Ziel/Wunsch], damit [Nutzen/Begründung].

**Beispiel:**
> Als Benutzer möchte ich mein Passwort ändern können, damit mein Account sicher bleibt.

**Merkmale von User-Stories:**
- Kurz und prägnant formuliert
- Beschreiben das "Was" und "Warum", nicht das "Wie"
- Dienen als Gesprächsgrundlage zwischen Entwicklern und Stakeholdern
- Werden oft mit Akzeptanzkriterien ergänzt, die die Anforderungen konkretisieren

**Vorteile:**
- Förderung der Nutzerorientierung
- Flexibilität bei der Umsetzung
- Einfache Priorisierung und Planung im Projekt

## Workshop

Ein Workshop ist eine strukturierte Arbeitsveranstaltung, bei der mehrere Teilnehmer gemeinsam an einem bestimmten Thema, Problem oder Ziel arbeiten. Workshops werden häufig in Projekten eingesetzt, um Wissen zu vermitteln, Anforderungen zu erarbeiten oder Lösungen zu entwickeln.

**Typische Ziele eines Workshops:**
- Gemeinsames Verständnis schaffen
- Anforderungen sammeln und priorisieren
- Ideen generieren (z.B. Brainstorming)
- Entscheidungen treffen
- Prototypen oder Konzepte erarbeiten

**Ablauf eines Workshops:**
1. **Vorbereitung:** Zielsetzung, Teilnehmerauswahl, Agenda und Materialien festlegen
2. **Durchführung:** Moderation, Gruppenarbeiten, Diskussionen, Visualisierung der Ergebnisse
3. **Nachbereitung:** Dokumentation der Ergebnisse, Ableitung von Maßnahmen

**Vorteile von Workshops:**
- Förderung der Zusammenarbeit und Kommunikation
- Nutzung des Wissens und der Erfahrungen aller Teilnehmer
- Schnelle und kreative Lösungsfindung

**Beispiel:**  
Ein Workshop mit Kunden und Entwicklern zur Erarbeitung von User-Stories für ein neues Softwareprojekt.

