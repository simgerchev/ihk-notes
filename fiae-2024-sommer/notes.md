# Entwicklung und Umsetzung von Algorithmen

## Inhaltsverzeichnis

- [Aktivitätsdiagramm](#aktivitätsdiagramm)
- [Black-Box-Test](#black-box-test)
- [Code-Coverage](#code-coverage)
- [E-Mail-Sicherheit](#e-mail-sicherheit)
- [Pseudocode](#pseudocode)
- [Regressionstests](#regressionstests)
- [Schreibtischtest](#schreibtischtest)
- [SQL](#sql)
- [UNION](#union)
- [White-Box-Test](#white-box-test)

# Planen eines Softwareproduktes

## Inhaltsverzeichnis

- [CRUD](#crud)
- [ERM](#erm)
- [HTTP-Methoden](#http-methoden)
- [HTTP-Request](#http-request)
- [HTTP-Statuscodes](#http-statuscodes)
- [Klassendiagramm](#klassendiagramm)
- [Mockups](#mockups)
- [Objektorientierung](#objektorientierung)
- [Pseudocode](#pseudocode)
- [Qualitätssicherung](#qualitätssicherung)
- [REST](#rest)
- [Self-Service](#self-service)
- [Sequenzdiagramm](#sequenzdiagramm)
- [Sicherheitsanforderungen](#sicherheitsanforderungen)
- [Stakeholder](#stakeholder)
- [Usability](#usability)
- [Use-Case-Diagramm](#use-case-diagramm)

## Aktivitätsdiagramm

```bash
cat ./fiae-2021-winter/notes.md
```

## Black-Box-Test

```bash
cat ./fiae-2021-winter/notes.md
```

## Code-Coverage

```bash
cat ./fiae-2022-sommer/notes.md
```

## E-Mail-Sicherheit

E-Mail-Sicherheit umfasst Maßnahmen und Technologien, um E-Mails vor unbefugtem Zugriff, Manipulation und Missbrauch zu schützen. Ziel ist es, die Vertraulichkeit, Integrität und Authentizität von E-Mails sicherzustellen.

**Wichtige Aspekte der E-Mail-Sicherheit:**
- **Verschlüsselung:** Schutz des Inhalts durch Verschlüsselung (z.B. S/MIME, PGP), damit nur berechtigte Empfänger die Nachricht lesen können.
- **Authentifizierung:** Sicherstellung, dass der Absender echt ist (z.B. SPF, DKIM, DMARC).
- **Spam- und Phishing-Schutz:** Filter zum Erkennen und Blockieren unerwünschter oder betrügerischer E-Mails.
- **Malware-Schutz:** Scannen von Anhängen und Links auf Schadsoftware.
- **Integrität:** Schutz vor Manipulation der E-Mail während der Übertragung.

**Best Practices:**
- Starke Passwörter und Zwei-Faktor-Authentifizierung für E-Mail-Konten verwenden
- Keine sensiblen Daten unverschlüsselt per E-Mail versenden
- Vorsicht beim Öffnen von Anhängen und Links unbekannter Absender
- Regelmäßige Updates und Sicherheits-Patches für E-Mail-Programme

**Beispiel für Verschlüsselung:**  
Mit S/MIME oder PGP werden E-Mails und Anhänge verschlüsselt und digital signiert, um Vertraulichkeit und Authentizität zu gewährleisten.

## Pseudocode

```bash
cat ./fiae-2021-winter/notes.md
```

## Regressionstests

Regressionstests sind Tests, die nach Änderungen am Code (z.B. Bugfixes, neue Features oder Refaktorierungen) durchgeführt werden, um sicherzustellen, dass bestehende Funktionen weiterhin korrekt arbeiten. Ziel ist es, unbeabsichtigte Fehler (Regressionen) frühzeitig zu erkennen.

**Eigenschaften von Regressionstests:**
- Wiederholen bereits durchgeführter Tests nach jeder Änderung
- Werden meist automatisiert ausgeführt (z.B. mit Unit-Tests)
- Decken möglichst viele bestehende Funktionen ab

**Vorteile:**
- Erhöhen die Stabilität und Zuverlässigkeit der Software
- Reduzieren das Risiko, dass neue Fehler eingeführt werden
- Unterstützen eine kontinuierliche Weiterentwicklung

**Beispiel:**  
Nach der Behebung eines Fehlers im Login-Modul werden alle relevanten Tests erneut ausgeführt, um sicherzustellen, dass das Login weiterhin funktioniert und keine anderen Bereiche unbeabsichtigt beeinflusst wurden.

## Schreibtischtest

```bash
cat ./fiae-2022-sommer/notes.md
```

## SQL

```bash
cat ./fiae-2021-winter/notes.md
```

## UNION

Der `UNION`-Operator in SQL wird verwendet, um die Ergebnisse mehrerer `SELECT`-Abfragen zu einer gemeinsamen Ergebnismenge zusammenzufassen. Dabei werden die Ergebnisse beider Abfragen untereinander angezeigt, doppelte Zeilen werden standardmäßig entfernt.

**Syntax:**
```sql
SELECT spalte1, spalte2 FROM tabelle1
UNION
SELECT spalte1, spalte2 FROM tabelle2;
```

**Wichtige Hinweise:**
- Die Anzahl und der Datentyp der Spalten müssen in beiden SELECTs übereinstimmen.
- Mit `UNION ALL` werden auch doppelte Zeilen angezeigt.

**Beispiel:**
```sql
SELECT name FROM kunden
UNION
SELECT name FROM lieferanten;
```
Dieses Beispiel gibt alle unterschiedlichen Namen aus beiden Tabellen zurück.

**Unterschied zu UNION ALL:**
- `UNION`: Entfernt doppelte Zeilen.
- `UNION ALL`: Gibt alle Zeilen aus, auch Duplikate.

## White-Box-Test

```bash
cat ./fiae-2021-winter/notes.md
```

## CRUD

CRUD steht für die vier grundlegenden Operationen bei der Verwaltung von Daten in Datenbanken oder Softwaresystemen:

- **Create:** Erstellen neuer Datensätze (z.B. INSERT in SQL)
- **Read:** Lesen oder Abfragen von Daten (z.B. SELECT in SQL)
- **Update:** Ändern bestehender Datensätze (z.B. UPDATE in SQL)
- **Delete:** Löschen von Datensätzen (z.B. DELETE in SQL)

**Beispiel in SQL:**
```sql
-- Create
INSERT INTO benutzer (name, email) VALUES ('Max', 'max@example.com');

-- Read
SELECT * FROM benutzer;

-- Update
UPDATE benutzer SET email = 'max.neu@example.com' WHERE name = 'Max';

-- Delete
DELETE FROM benutzer WHERE name = 'Max';
```

CRUD-Operationen bilden die Basis für viele Anwendungen, insbesondere für Datenbank- und Webanwendungen.

## ERM

```bash
cat ./fiae-2021-winter/notes.md
```

## HTTP-Methoden

HTTP-Methoden sind die Befehle, mit denen Clients (z.B. Browser) mit Servern im Web kommunizieren. Sie bestimmen, welche Aktion auf einer Ressource (z.B. einer Webseite oder API) ausgeführt werden soll.

**Wichtige HTTP-Methoden:**
- **GET:** Fordert Daten von einer Ressource an (nur lesen, keine Änderung).
- **POST:** Sendet Daten an den Server, um eine neue Ressource zu erstellen.
- **PUT:** Aktualisiert eine bestehende Ressource vollständig.
- **PATCH:** Aktualisiert eine bestehende Ressource teilweise.
- **DELETE:** Löscht eine Ressource.
- **HEAD:** Wie GET, aber ohne Antwortinhalt (nur Header).
- **OPTIONS:** Fragt ab, welche Methoden für eine Ressource unterstützt werden.

**Beispiel für eine REST-API:**
- `GET /benutzer/1` – Gibt die Daten des Benutzers mit der ID 1 zurück.
- `POST /benutzer` – Legt einen neuen Benutzer an.
- `PUT /benutzer/1` – Überschreibt die Daten des Benutzers mit der ID 1.
- `DELETE /benutzer/1` – Löscht den Benutzer mit der ID 1.

**Hinweis:**  
Die richtige Verwendung der HTTP-Methoden ist wichtig für die Einhaltung von Webstandards und die Sicherheit von Webanwendungen.

## HTTP-Request

Ein HTTP-Request (HTTP-Anfrage) ist eine Nachricht, die ein Client (z.B. Webbrowser) an einen Server sendet, um eine bestimmte Aktion auf einer Ressource auszuführen (z.B. Webseite abrufen, Daten senden).

**Bestandteile eines HTTP-Requests:**
- **Request-Line:** Enthält die HTTP-Methode, den Pfad zur Ressource und die HTTP-Version  
  z.B. `GET /index.html HTTP/1.1`
- **Header:** Zusätzliche Informationen wie Host, User-Agent, Accept, Content-Type usw.
- **Body (optional):** Enthält Daten, die an den Server gesendet werden (z.B. bei POST/PUT)

**Beispiel für einen einfachen HTTP-Request:**
```
GET /produkte HTTP/1.1
Host: www.beispiel.de
User-Agent: Mozilla/5.0
Accept: text/html
```

**Beispiel für einen POST-Request mit Body:**
```
POST /login HTTP/1.1
Host: www.beispiel.de
Content-Type: application/x-www-form-urlencoded
Content-Length: 27

username=max&password=geheim
```

**Ablauf:**
1. Client sendet HTTP-Request an den Server.
2. Server verarbeitet die Anfrage und sendet eine HTTP-Response zurück.

**Hinweis:**  
HTTP-Requests sind die Grundlage für die Kommunikation im Web und werden von allen Webanwendungen genutzt.

## HTTP-Statuscodes

HTTP-Statuscodes sind dreistellige Zahlen, die der Server als Antwort auf einen HTTP-Request zurückgibt. Sie informieren den Client über das Ergebnis der Anfrage.

**Wichtige Statuscode-Kategorien:**
- **1xx (Information):** Anfrage wird verarbeitet (z.B. 100 Continue)
- **2xx (Erfolg):** Anfrage war erfolgreich (z.B. 200 OK, 201 Created)
- **3xx (Umleitung):** Weitere Schritte erforderlich (z.B. 301 Moved Permanently, 302 Found)
- **4xx (Client-Fehler):** Fehler beim Client (z.B. 400 Bad Request, 401 Unauthorized, 403 Forbidden, 404 Not Found)
- **5xx (Server-Fehler):** Fehler beim Server (z.B. 500 Internal Server Error, 502 Bad Gateway, 503 Service Unavailable)

**Beispiele:**
- **200 OK:** Anfrage erfolgreich, Antwort im Body enthalten
- **201 Created:** Neue Ressource wurde erfolgreich erstellt
- **400 Bad Request:** Ungültige Anfrage (z.B. Syntaxfehler)
- **401 Unauthorized:** Authentifizierung erforderlich oder fehlgeschlagen
- **403 Forbidden:** Zugriff verweigert
- **404 Not Found:** Ressource nicht gefunden
- **500 Internal Server Error:** Allgemeiner Serverfehler

**Hinweis:**  
Statuscodes helfen bei der Fehleranalyse und sind essenziell für die Kommunikation zwischen Client und Server.

## Klassendiagramm

```bash
cat ./fiae-2021-winter/notes.md
```

## Mockups

```bash
cat ./fiae-2023-winter/notes.md
```

## Objektorientierung

```bash
cat ./fiae-2023-sommer/notes.md
```

## Qualitätssicherung

```bash
cat ./fiae-2023-sommer/notes.md
```

## REST

REST steht für **Representational State Transfer** und ist ein Architekturstil für die Entwicklung von Webservices. REST-basierte Schnittstellen (APIs) ermöglichen die Kommunikation zwischen Systemen über das HTTP-Protokoll.

**Grundprinzipien von REST:**
- **Ressourcenorientierung:** Jede Information (z.B. Benutzer, Produkt) wird als Ressource mit einer eindeutigen URL dargestellt.
- **Verwendung von HTTP-Methoden:** Aktionen auf Ressourcen werden mit HTTP-Methoden durchgeführt (GET, POST, PUT, DELETE, PATCH).
- **Zustandslosigkeit:** Jeder Request enthält alle nötigen Informationen; der Server speichert keinen Sitzungszustand.
- **Repräsentationen:** Ressourcen werden meist im JSON- oder XML-Format übertragen.
- **Einheitliche Schnittstelle:** Klare und konsistente API-Struktur.

**Beispiel für REST-URLs:**
- `GET /benutzer/1` – Gibt die Daten des Benutzers mit der ID 1 zurück.
- `POST /produkte` – Legt ein neues Produkt an.
- `DELETE /bestellungen/5` – Löscht die Bestellung mit der ID 5.

**Vorteile von REST:**
- Einfach, leichtgewichtig und gut verständlich
- Plattform- und sprachunabhängig
- Gut geeignet für Webanwendungen und mobile Apps

**Hinweis:**  
REST ist heute der Standard für moderne Web-APIs und wird von vielen Frameworks und Tools unterstützt.

## Self-Service

Self-Service bezeichnet Systeme oder Funktionen, die es Nutzern ermöglichen, Aufgaben eigenständig und ohne direkte Unterstützung durch einen Mitarbeiter zu erledigen. Ziel ist es, Prozesse zu automatisieren, die Effizienz zu steigern und die Nutzerzufriedenheit zu erhöhen.

**Beispiele für Self-Service:**
- Online-Banking: Überweisungen und Kontoabfragen ohne Bankmitarbeiter
- Passwort-Zurücksetzung über ein Webportal
- Self-Service-Portale für IT-Support (z.B. Tickets erstellen, FAQs nutzen)
- Online-Bestellung und -Verwaltung von Produkten oder Dienstleistungen

**Vorteile von Self-Service:**
- Entlastung von Support- und Serviceteams
- Schnellere Problemlösung für Nutzer
- Rund-um-die-Uhr-Verfügbarkeit
- Reduzierung von Kosten

**Wichtige Aspekte:**
- Benutzerfreundliche Gestaltung (Usability)
- Klare Anleitungen und Hilfestellungen
- Sicherheit und Datenschutz bei sensiblen Vorgängen

Self-Service-Lösungen sind heute in vielen Bereichen Standard und tragen wesentlich zur Digitalisierung von Geschäftsprozessen bei.

## Sequenzdiagramm

```bash
cat ./fiae-2022-sommer/notes.md
```

## Sicherheitsanforderungen

Sicherheitsanforderungen beschreiben, welche Maßnahmen und Eigenschaften ein System erfüllen muss, um Daten und Funktionen vor unbefugtem Zugriff, Missbrauch, Manipulation oder Verlust zu schützen. Sie sind ein wichtiger Bestandteil bei der Planung und Entwicklung von Software.

**Typische Sicherheitsanforderungen:**
- **Vertraulichkeit:** Schutz sensibler Daten vor unbefugtem Zugriff (z.B. durch Verschlüsselung)
- **Integrität:** Sicherstellung, dass Daten nicht unbemerkt verändert werden können
- **Verfügbarkeit:** System und Daten müssen zuverlässig erreichbar sein
- **Authentifizierung:** Überprüfung der Identität von Benutzern (z.B. Login mit Passwort, Zwei-Faktor-Authentifizierung)
- **Autorisierung:** Steuerung, welche Aktionen ein Benutzer ausführen darf (z.B. Rollen- und Rechtemanagement)
- **Nachvollziehbarkeit:** Protokollierung von Zugriffen und Änderungen (Logging, Audit-Trails)
- **Datenschutz:** Einhaltung gesetzlicher Vorgaben zum Schutz personenbezogener Daten (z.B. DSGVO)

**Beispiele für Maßnahmen:**
- Einsatz von Firewalls und Virenschutz
- Verschlüsselung von Datenübertragung und -speicherung
- Regelmäßige Backups
- Sichere Passwortrichtlinien
- Zugriffsbeschränkungen und Rechteverwaltung

Sicherheitsanforderungen sollten frühzeitig im Projekt definiert und regelmäßig überprüft werden, um Risiken zu minimieren und Compliance sicherzustellen.

## Stakeholder

```bash
cat ./fiae-2023-winter/notes.md
```

## Usability

Usability (Benutzerfreundlichkeit) beschreibt, wie einfach und effizient ein Benutzer ein System, eine Software oder eine Website bedienen kann. Ziel ist es, die Nutzung so angenehm und fehlerfrei wie möglich zu gestalten.

**Wichtige Aspekte der Usability:**
- **Intuitive Bedienung:** Nutzer finden sich ohne lange Einarbeitung zurecht.
- **Konsistentes Design:** Einheitliche Gestaltung und wiederkehrende Elemente erleichtern die Orientierung.
- **Fehlertoleranz:** Das System hilft, Fehler zu vermeiden oder leicht zu korrigieren.
- **Effizienz:** Aufgaben können schnell und mit wenig Aufwand erledigt werden.
- **Zufriedenheit:** Nutzer haben ein positives Erlebnis bei der Verwendung.

**Beispiele für gute Usability:**
- Klare Navigation und verständliche Menüs
- Hilfetexte und Tooltips
- Übersichtliche und aufgeräumte Oberflächen
- Schnelle Ladezeiten

Usability ist ein zentraler Erfolgsfaktor für Software und sollte bereits im Designprozess berücksichtigt und regelmäßig getestet werden (z.B. durch Usability-Tests mit echten Nutzern).

## Use-Case-Diagramm

```bash
cat ./fiae-2022-winter/notes.md
```
