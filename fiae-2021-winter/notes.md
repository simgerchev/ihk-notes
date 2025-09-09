# Entwicklung und Umsetzung von Algorithmen
## Aktivitätsdiagramm

<img src="aktivitätsdiagramm.png">

## SQL Commands  

### 1. SELECT – Daten abfragen
```sql
SELECT * FROM kunden;
SELECT name, email FROM kunden WHERE stadt = 'Berlin';
```

### 2. INSERT – Neue Daten einfügen
```sql
INSERT INTO kunden (name, email, stadt) VALUES ('Max Mustermann', 'max@email.de', 'Berlin');
```

### 3. UPDATE – Daten ändern
```sql
UPDATE kunden SET email = 'neu@email.de' WHERE name = 'Max Mustermann';
```

### 4. DELETE – Daten löschen
```sql
DELETE FROM kunden WHERE name = 'Max Mustermann';
```

### 5. CREATE TABLE – Neue Tabelle erstellen
```sql
CREATE TABLE kunden (
	id INT PRIMARY KEY,
	name VARCHAR(100),
	email VARCHAR(100),
	stadt VARCHAR(50)
);
```

### 6. ALTER TABLE – Tabelle ändern
```sql
ALTER TABLE kunden ADD geburtsdatum DATE;
```

### 7. DROP TABLE – Tabelle löschen
```sql
DROP TABLE kunden;
```

### 8. JOIN – Tabellen verbinden
```sql
SELECT kunden.name, bestellungen.datum
FROM kunden
JOIN bestellungen ON kunden.id = bestellungen.kunden_id;
```

## Prozessanalyse 

Die Prozessanalyse ist ein wichtiger Bestandteil der Fachinformatik. Sie dient dazu, Arbeitsabläufe in Unternehmen zu verstehen, Schwachstellen zu erkennen und Verbesserungen vorzuschlagen. Ziel ist es, Prozesse effizienter und fehlerfreier zu gestalten.

**Wichtige Schritte der Prozessanalyse:**
- Prozess identifizieren und abgrenzen: Welcher Ablauf soll betrachtet werden?
- Ist-Zustand aufnehmen: Den aktuellen Ablauf dokumentieren (z.B. mit Diagrammen, Interviews, Beobachtungen).
- Ablaufschritte, Beteiligte und Ressourcen erfassen: Wer macht was, wann und womit?
- Schwachstellen und Engpässe erkennen: Wo treten Fehler, Verzögerungen oder unnötige Aufwände auf?
- Verbesserungsvorschläge erarbeiten: Wie kann der Prozess effizienter, sicherer oder kostengünstiger gestaltet werden?

**Typische Werkzeuge und Methoden:**
- Flussdiagramm / Aktivitätsdiagramm: Visualisierung der Ablaufschritte
- BPMN (Business Process Model and Notation): Standardisierte Modellierung von Geschäftsprozessen
- Interview und Beobachtung: Informationen direkt von den Beteiligten sammeln

**Bedeutung für Fachinformatiker:**
- Prozesse analysieren, um Anforderungen für Software und IT-Systeme zu ermitteln
- Optimierungspotenziale erkennen und digitale Lösungen vorschlagen
- Schnittstellen zwischen Mensch, Maschine und Software verstehen

## Pseudocode 

**Aufgabe:**
Schreibe einen Pseudocode, der eine Liste von Zahlen durchläuft und sowohl die größte als auch die kleinste Zahl sowie deren Positionen in der Liste findet.

**Lösung (Pseudocode):**
```
Eingabe: liste mit Zahlen
Setze größte = erstes Element der liste
Setze kleinste = erstes Element der liste
Setze pos_größte = 0
Setze pos_kleinste = 0

Für i von 0 bis Länge der liste - 1:
	Wenn liste[i] > größte:
		größte = liste[i]
		pos_größte = i
	Wenn liste[i] < kleinste:
		kleinste = liste[i]
		pos_kleinste = i

Ausgabe: größte, pos_größte, kleinste, pos_kleinste
```