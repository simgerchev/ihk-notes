# Entwicklung und Umsetzung von Algorithmen

## Inhaltsverzeichnis

- [Datenimport](#datenimport)
- [Datenqualität](#datenqualität)
- [Klassendiagramm](#klassendiagramm)
- [Objektorientierung](#objektorientierung)
- [Pseudocode](#pseudocode)
- [Relationales Datenmodell](#relationales-datenmodell)
- [SQL](#sql)

# Planen eines Softwareproduktes

## Inhaltsverzeichnis

- [Datenschutz](#datenschutz)
- [Design Patterns](#design-patterns)
- [Ethernet](#ethernet)
- [IoT](#iot)
- [MAC](#mac)
- [Projektmanagement](#projektmanagement)
- [Pseudocode](#pseudocode)
- [SAN](#san)
- [Vorgehensmodelle](#vorgehensmodelle)
- [Zustandsdiagramm](#zustandsdiagramm)

## Datenimport

Datenimport bezeichnet den Vorgang, Daten aus externen Quellen in ein System oder eine Datenbank zu übernehmen. Ziel ist es, vorhandene Daten (z.B. aus Dateien, anderen Datenbanken oder externen Anwendungen) für die weitere Verarbeitung oder Analyse verfügbar zu machen.

**Typische Quellen für den Datenimport:**
- CSV-, Excel- oder Textdateien
- Datenbanken (z.B. MySQL, PostgreSQL)
- Webservices und APIs
- XML- oder JSON-Dateien

**Ablauf eines Datenimports:**
1. **Datenquelle auswählen:** Festlegen, woher die Daten stammen.
2. **Daten einlesen:** Daten werden aus der Quelle geladen (z.B. Datei öffnen, API-Abfrage).
3. **Daten prüfen und bereinigen:** Überprüfung auf Fehler, Duplikate oder Inkonsistenzen.
4. **Daten transformieren:** Anpassung des Formats oder der Struktur an das Zielsystem.
5. **Daten speichern:** Übernahme der Daten in die Zieldatenbank oder Anwendung.

**Beispiel:**  
Import von Kundendaten aus einer CSV-Datei in eine Datenbank.

**Wichtige Aspekte:**
- Datenqualität sicherstellen (z.B. durch Validierung)
- Fehlerprotokollierung und Nachvollziehbarkeit
- Datenschutz und Sicherheit beim Umgang mit sensiblen Daten

## Datenqualität

Datenqualität beschreibt, wie gut Daten für ihren vorgesehenen Zweck geeignet sind. Hohe Datenqualität ist entscheidend für die Zuverlässigkeit von Analysen, Berichten und Geschäftsprozessen.

**Merkmale guter Datenqualität:**
- **Vollständigkeit:** Alle benötigten Daten sind vorhanden.
- **Korrektheit:** Die Daten sind sachlich und inhaltlich richtig.
- **Konsistenz:** Daten sind widerspruchsfrei (z.B. keine unterschiedlichen Werte für dasselbe Attribut).
- **Aktualität:** Die Daten sind auf dem neuesten Stand.
- **Eindeutigkeit:** Keine doppelten oder mehrdeutigen Einträge.
- **Relevanz:** Die Daten sind für den jeweiligen Zweck geeignet.

**Maßnahmen zur Sicherung der Datenqualität:**
- Validierung und Plausibilitätsprüfungen beim Datenimport
- Regelmäßige Datenbereinigung (z.B. Duplikate entfernen)
- Automatisierte und manuelle Qualitätskontrollen
- Schulung der Mitarbeiter im Umgang mit Daten
- Dokumentation der Datenquellen und -prozesse

**Beispiel:**  
Bei einer Kundendatenbank bedeutet hohe Datenqualität, dass alle Adressen korrekt, vollständig und aktuell sind und keine doppelten Kundeneinträge existieren.

## Klassendiagramm

```bash
cat ./fiae-2022-winter/notes.md
```

## Objektorientierung

```bash
cat ./fiae-2023-sommer/notes.md
```

## Pseudocode

```bash
cat ./fiae-2021-winter/notes.md
```

## Relationales Datenmodell

```bash
cat ./fiae-2021-winter/notes.md
```

## SQL

```bash
cat ./fiae-2021-winter/notes.md
```

---
---
## Datenschutz

Datenschutz umfasst alle Maßnahmen, die den Schutz personenbezogener Daten vor Missbrauch, unbefugtem Zugriff und Verlust sicherstellen. Ziel ist es, die Privatsphäre von Personen zu wahren und gesetzliche Vorgaben (z.B. DSGVO) einzuhalten.

**Wichtige Prinzipien des Datenschutzes:**
- **Datenminimierung:** Es werden nur so viele Daten erhoben und gespeichert, wie unbedingt nötig.
- **Zweckbindung:** Daten dürfen nur für den angegebenen Zweck verwendet werden.
- **Transparenz:** Betroffene müssen über die Verarbeitung ihrer Daten informiert werden.
- **Integrität und Vertraulichkeit:** Schutz vor unbefugtem Zugriff und Manipulation.
- **Rechte der Betroffenen:** Personen haben das Recht auf Auskunft, Berichtigung, Löschung und Widerspruch.

**Maßnahmen zum Datenschutz:**
- Verschlüsselung von Datenübertragung und -speicherung
- Zugriffsbeschränkungen und Rollenmanagement
- Regelmäßige Schulungen der Mitarbeiter
- Datenschutz-Folgenabschätzung bei neuen Projekten
- Dokumentation aller Datenverarbeitungsprozesse

**Beispiel:**  
Bei der Entwicklung einer Webanwendung müssen personenbezogene Daten (z.B. Name, E-Mail) sicher gespeichert und verarbeitet werden. Nutzer müssen über die Datennutzung informiert werden und der Verarbeitung zustimmen.

**Gesetzliche Grundlage:**  
In Europa ist die Datenschutz-Grundverordnung (DSGVO) maßgeblich für den Umgang mit personenbezogenen Daten.

## Design Patterns

```bash
cat ./fiae-2023-sommer/notes.md
```

## Ethernet

Ethernet ist eine weit verbreitete Technologie für lokale Netzwerke (LANs), die den kabelgebundenen Datenaustausch zwischen Geräten ermöglicht. Es definiert sowohl die physikalischen Eigenschaften (z.B. Kabel, Stecker) als auch die Regeln für die Datenübertragung (Protokolle).

**Eigenschaften von Ethernet:**
- Standardisiert durch IEEE 802.3
- Übertragung meist über Twisted-Pair-Kabel (z.B. Cat5e, Cat6) oder Glasfaser
- Typische Übertragungsgeschwindigkeiten: 10 Mbit/s, 100 Mbit/s (Fast Ethernet), 1 Gbit/s (Gigabit Ethernet), 10 Gbit/s und mehr
- Verwendung von MAC-Adressen zur eindeutigen Identifikation von Geräten im Netzwerk
- Arbeitet auf Schicht 1 (Physikalische Schicht) und Schicht 2 (Sicherungsschicht) des OSI-Modells

**Vorteile:**
- Hohe Übertragungsgeschwindigkeit und Zuverlässigkeit
- Geringe Latenzzeiten
- Kostengünstige und weit verbreitete Technologie

**Beispielanwendung:**  
Verbindung von Computern, Druckern und Servern in einem Unternehmensnetzwerk über Switches und Ethernet-Kabel.

## IoT

IoT steht für **Internet of Things** (Internet der Dinge) und bezeichnet die Vernetzung von physischen Geräten (z.B. Sensoren, Maschinen, Haushaltsgeräte) über das Internet. Diese Geräte können Daten erfassen, austauschen und teilweise eigenständig Aktionen ausführen.

**Eigenschaften und Ziele von IoT:**
- Geräte sind mit Sensoren, Aktoren und Kommunikationsmodulen ausgestattet
- Automatisierte Datenerfassung und -übertragung
- Fernsteuerung und Überwachung von Geräten möglich
- Optimierung von Prozessen durch Auswertung der gesammelten Daten

**Beispiele für IoT-Anwendungen:**
- Smart Home (z.B. vernetzte Thermostate, Lampen, Sicherheitskameras)
- Industrie 4.0 (z.B. Maschinenüberwachung, Predictive Maintenance)
- Gesundheitswesen (z.B. vernetzte Medizingeräte, Fitness-Tracker)
- Logistik (z.B. Sendungsverfolgung, intelligente Lagerhaltung)

**Herausforderungen:**
- Sicherheit und Datenschutz (Schutz vor unbefugtem Zugriff)
- Standardisierung der Kommunikation zwischen Geräten
- Umgang mit großen Datenmengen (Big Data)

IoT ist ein zentrales Element der Digitalisierung und ermöglicht neue Geschäftsmodelle und Effizienzsteigerungen in vielen Bereichen.

## MAC

MAC steht für **Media Access Control** und bezeichnet sowohl eine Adressierungsmethode als auch ein Teilprotokoll in Netzwerken.

**1. MAC-Adresse:**
- Eine MAC-Adresse ist eine weltweit eindeutige Hardware-Adresse, die jedem Netzwerkgerät (z.B. Netzwerkkarte, Switch) zugewiesen wird.
- Sie besteht aus 48 Bit (6 Byte) und wird meist in Hexadezimal-Schreibweise dargestellt (z.B. 00:1A:2B:3C:4D:5E).
- Wird auf der Sicherungsschicht (Layer 2) des OSI-Modells verwendet, um Geräte im lokalen Netzwerk eindeutig zu identifizieren.

**2. Media Access Control (Protokoll):**
- Regelt den Zugriff mehrerer Geräte auf das Übertragungsmedium (z.B. Ethernet-Kabel).
- Bestimmt, wann ein Gerät senden darf, um Kollisionen zu vermeiden (z.B. CSMA/CD bei Ethernet).

**Wichtige Aspekte:**
- MAC-Adressen sind fest in der Hardware gespeichert, können aber teilweise softwareseitig geändert werden.
- Sie sind notwendig für die Kommunikation innerhalb eines lokalen Netzwerks (LAN).

**Beispiel:**  
Wenn ein Computer ein Datenpaket im LAN verschickt, wird dieses mit der MAC-Adresse des Empfängers adressiert, damit nur das richtige Gerät die Daten empfängt.

## Projektmanagement

Projektmanagement umfasst die Planung, Steuerung und Überwachung von Projekten, um definierte Ziele innerhalb eines vorgegebenen Zeit-, Kosten- und Qualitätsrahmens zu erreichen. Es sorgt dafür, dass Ressourcen effizient eingesetzt und Risiken minimiert werden.

**Wichtige Aufgaben im Projektmanagement:**
- Zieldefinition und Projektplanung
- Ressourcenmanagement (Personal, Zeit, Budget)
- Aufgabenverteilung und Koordination des Teams
- Überwachung des Projektfortschritts (Meilensteine, Statusberichte)
- Risikomanagement und Problemlösung
- Kommunikation mit Stakeholdern

**Phasen eines Projekts:**
1. **Projektinitiierung:** Projektziele, Anforderungen und Machbarkeit klären
2. **Projektplanung:** Zeitplan, Ressourcen, Budget und Aufgaben festlegen
3. **Projektdurchführung:** Umsetzung der geplanten Aufgaben
4. **Projektüberwachung:** Kontrolle des Fortschritts und Anpassung bei Abweichungen
5. **Projektabschluss:** Abnahme, Dokumentation und Nachbereitung

**Methoden und Werkzeuge:**
- Klassische Methoden (z.B. Wasserfallmodell)
- Agile Methoden (z.B. Scrum, Kanban)
- Projektmanagement-Tools (z.B. Jira, MS Project, Trello)

Erfolgreiches Projektmanagement ist entscheidend für das Erreichen der Projektziele und die Zufriedenheit aller Beteiligten.

## SAN

SAN steht für **Storage Area Network** und bezeichnet ein spezielles, eigenständiges Netzwerk, das ausschließlich der Verbindung von Servern mit Speichergeräten (z.B. Festplatten, Tape Libraries) dient. Ziel eines SAN ist es, Speicherressourcen zentral bereitzustellen und flexibel mehreren Servern zur Verfügung zu stellen.

**Eigenschaften eines SAN:**
- Getrenntes Netzwerk für Speicherzugriffe (meist über Fibre Channel oder iSCSI)
- Hohe Übertragungsgeschwindigkeiten und geringe Latenz
- Zentrale Verwaltung und Zuweisung von Speicherplatz
- Skalierbarkeit: Speicher kann einfach erweitert werden

**Vorteile:**
- Effiziente Nutzung und Verwaltung großer Datenmengen
- Erhöhte Ausfallsicherheit durch Redundanz und Backup-Lösungen
- Entlastung des normalen LAN, da Speicherzugriffe über das SAN laufen

**Beispielanwendung:**  
In Rechenzentren werden Server über ein SAN mit zentralen Speicherpools verbunden, sodass Daten flexibel und performant bereitgestellt werden können.

**Unterschied zu NAS:**  
Ein SAN stellt blockbasierten Speicher zur Verfügung (wie eine lokale Festplatte), während ein NAS (Network Attached Storage) dateibasierten Speicher über das Netzwerk bereitstellt.

## Vorgehensmodelle

```bash
cat ./fiae-2022-sommer/notes.md
```
