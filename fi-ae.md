# I
## Vorgehensmodelle 
### Klassische Vorgehensmodelle (Plangetrieben / "Wasserfallartig")
Diese Modelle sind eher linear und sequenziell aufgebaut – die Anforderungen werden zu Beginn festgelegt und Änderungen sind später schwer umzusetzen.
- Wasserfallmodell
Phasen: Anforderungsanalyse → Systementwurf → Implementierung → Test → Betrieb → Wartung
Jede Phase schließt die vorherige ab
Nachteile: Unflexibel, Änderungen teuer
- V-Modell (V-Modell XT in Deutschland)
Erweiterung des Wasserfalls mit Fokus auf Qualitätssicherung
Die linke Seite: Spezifikation & Design
Die rechte Seite: Teststufen, die den Spezifikationen zugeordnet sind
Wird oft in der öffentlichen Verwaltung & sicherheitskritischen Bereichen verwendet
- Spiralmodell
Kombination aus iterativem Vorgehen und Risikomanagement
Jede Schleife besteht aus: Planung → Risikoanalyse → Entwicklung → Test
Vorteil: Risikobewusstes Vorgehen
Aufwendiger als einfache Modelle
- RUP (Rational Unified Process)
Iteratives Vorgehensmodell mit klaren Rollen, Aktivitäten und Artefakten
Phasen: Inception → Elaboration → Construction → Transition
Starke Tool-Unterstützung (z. B. durch IBM Rational Suite)
### Agile Vorgehensmodelle
Agile Modelle setzen auf Flexibilität, inkrementelle Entwicklung, Kundenfeedback und Teamautonomie. Änderungen sind jederzeit willkommen.
- Scrum
Iterativ-inkrementelles Framework mit festen Rollen:
Product Owner
Scrum Master
Entwicklungsteam
Ablauf:
Product Backlog
Sprint Planning
Daily Scrum
Sprint Review
Sprint Retrospective
Sprints: Zeitlich begrenzte Iterationen (meist 2–4 Wochen)
- Kanban
Visualisierung des Workflows auf einem Kanban-Board (z. B. TODO, IN PROGRESS, DONE)
Fokus: Kontinuierlicher Fluss statt Iterationen
WIP-Limits (Work in Progress) vermeiden Überlastung
- Extreme Programming (XP)
Starke Betonung auf technischer Exzellenz und Teamarbeit
Praktiken:
Pair Programming
Test-Driven Development (TDD)
Continuous Integration
Refactoring
Sehr kundennah, häufige Releases
- Feature-Driven Development (FDD)
Modell mit Fokus auf Feature-getriebene Planung
Schritte:
Gesamtmodell entwickeln
Feature-Liste erstellen
Feature-Design und -Implementierung in kurzen Iterationen
## Anforderungen
- Funktionale Anforderungen
Beschreiben was ein System tun soll – also die konkreten Funktionen und Abläufe, die es ausführen muss.
    - 🔧 Beispiele:
Der Benutzer kann sich mit Benutzername und Passwort anmelden.
Das System sendet eine E-Mail nach erfolgreicher Registrierung.
Ein Kunde kann Produkte in den Warenkorb legen und bestellen.
Nur Admins dürfen Benutzerkonten löschen.
Das System speichert jede Transaktion in einer Datenbank.
    - 🔍 Typische Bereiche:
Benutzerinteraktionen
Geschäftsprozesse
API-Endpunkte
Datenbankfunktionen
Berechtigungen/Rollen
- Nicht-funktionale Anforderungen
Beschreiben wie gut oder unter welchen Bedingungen ein System funktionieren soll – also Qualitätsmerkmale oder Randbedingungen.
    - 🛠️ Beispiele:
Das System muss innerhalb von 2 Sekunden auf Benutzeranfragen reagieren.
Die Webanwendung muss auf mobilen Geräten nutzbar sein (Responsivität).
Das System muss 24/7 verfügbar sein (Verfügbarkeit 99,9 %).
Der Quellcode soll dokumentiert und wartbar sein.
Die Anwendung soll DSGVO-konform sein.
    - 📂 Typische Kategorien:
        - Performance	
            - Antwortzeiten, Durchsatz, Ladezeiten
        - Zuverlässigkeit	
            - Fehlertoleranz, Verfügbarkeit
        - Sicherheit
            - Zugriffskontrolle, Verschlüsselung, Datenschutz
        - Benutzbarkeit	
            - UI/UX, Barrierefreiheit
        - Portabilität	
            - Plattformunabhängigkeit, mobile Nutzung
        - Wartbarkeit	
            - Dokumentation, Modularität, Testbarkeit
        - Skalierbarkeit	
            - Fähigkeit, bei Lastzunahme zu wachsen
        - Kompatibilität	
            - Integration mit anderen Systemen, Software/Hardware
        - Rechtliche Vorgaben	
            - DSGVO, Lizenzpflichten, Industriestandards

## UML Klassendiagramme 
### Was ist ein UML-Klassendiagramm?

Ein **UML-Klassendiagramm** beschreibt die statische Struktur eines Systems mit Klassen, Attributen, Methoden und deren Beziehungen.

---

### Beispiel: Vererbung

