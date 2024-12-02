# Bandlaufwerk- und Bandspeicherplanung

## Planung der Bandlaufwerke

- **Mehrere Bandlaufwerke erwägen**: 
  - Wenn ein einzelnes Bandlaufwerk eines Autoloaders nicht ausreicht, um Daten schnell genug zu sichern, sollte eine Library mit mehreren Laufwerken in Betracht gezogen werden.
  - **Vorteile**:
    - Parallele Durchführung mehrerer Sicherungsjobs.
    - Parallele Sicherung und Wiederherstellung.
    - Ausfallsicherheit: Bei Ausfall eines Laufwerks kann das zweite fortsetzen.

## Anzahl der Bänder im Laufwerk

- **Bänderanzahl bestimmen**:
  - Es sollten genügend Bänder für den gesamten Sicherungszeitraum vorhanden sein.
  - Mindestens ein Magazin für eine Wochensicherung, besser zwei, sollte eingelegt werden können.
  - Bei einer Library sollten mindestens so viele Schächte vorhanden sein, wie für die geplante Sicherungsdauer benötigt werden.

## Beispiel zur Planung

- **Sicherungsszenario**:
  - **Datenvolumen**: 800 GByte pro Woche in der Vollsicherung.
  - **Tägliche Änderung**: 40 GByte.
  - **Laufwerk**: LTO-1 mit 100 GByte Kapazität.
  
- **Schachtbedarf**:
  - **Für Wochensicherung**: Mindestens 22 Schächte für zwei Wochen Aufbewahrung.
  - **Für Vollsicherung mit Magazinwechsel**: 44 Schächte.
  - **Für tägliche Vollsicherung bei 7-Tage-Woche**: 56 Schächte.

## Wichtige Überlegungen

- Frühzeitige Planung der Sicherungsstrategie ist entscheidend.
- Entscheidung über die Datenmenge, die gesichert werden soll, und die Intervalle für den Bandwechsel in der Library.
