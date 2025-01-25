# Anleitung zur Erstellung eines verschlüsselten Containers mit VeraCrypt

## 1. VeraCrypt herunterladen und installieren

- **Download:** Laden Sie die neueste Version von VeraCrypt von der offiziellen Website herunter.
- **Installation:** Führen Sie das heruntergeladene Installationsprogramm aus und folgen Sie den Anweisungen auf dem Bildschirm, um VeraCrypt zu installieren.

## 2. Erstellen eines neuen verschlüsselten Containers

- **VeraCrypt starten:** Öffnen Sie die VeraCrypt-Anwendung.
- **Volume erstellen:**
  - Klicken Sie auf "Create Volume".
  - Wählen Sie "Create an encrypted file container" und klicken Sie auf "Next".
- **Volume-Typ auswählen:**
  - Wählen Sie "Standard VeraCrypt volume" und klicken Sie auf "Next".
- **Datei auswählen:**
  - Klicken Sie auf "Select File...".
  - Navigieren Sie zu dem gewünschten Speicherort, geben Sie einen Dateinamen für den Container ein (z. B. "Verschlüsselt.hc") und klicken Sie auf "Speichern".
  - Klicken Sie auf "Next".
- **Verschlüsselungsoptionen:**
  - Lassen Sie die Standardwerte für Verschlüsselungs- und Hash-Algorithmus ausgewählt und klicken Sie auf "Next".
- **Volume-Größe festlegen:**
  - Geben Sie die gewünschte Größe für den Container ein (z. B. "5 GB") und klicken Sie auf "Next".
- **Passwort festlegen:**
  - Geben Sie ein sicheres Passwort ein und bestätigen Sie es.
  - Hinweis: Verwenden Sie ein starkes Passwort, um die Sicherheit zu gewährleisten.
  - Klicken Sie auf "Next".
- **Dateisystem und Formatierung:**
  - Wählen Sie das gewünschte Dateisystem (z. B. "NTFS" für Windows) aus.
  - Bewegen Sie die Maus zufällig innerhalb des Fensters, um die Kryptografiestärke zu erhöhen.
  - Klicken Sie auf "Format", um den Container zu erstellen.
  - Nach Abschluss klicken Sie auf "Exit".

## 3. Den Container einbinden (mounten)

- **Laufwerksbuchstabe auswählen:**
  - Wählen Sie in VeraCrypt einen freien Laufwerksbuchstaben aus der Liste aus.
- **Container einbinden:**
  - Klicken Sie auf "Select File..." und wählen Sie die zuvor erstellte Container-Datei aus.
  - Klicken Sie auf "Mount".
  - Geben Sie das Passwort ein und klicken Sie auf "OK".
- **Zugriff auf den Container:**
  - Der Container ist nun als virtuelles Laufwerk im Datei-Explorer verfügbar.
  - Sie können Dateien hinzufügen, bearbeiten oder löschen, als wäre es ein normales Laufwerk.

## 4. Den Container aushängen (dismounten)

- **Aushängen:**
  - Nach dem Arbeiten mit dem Container kehren Sie zu VeraCrypt zurück.
  - Wählen Sie das eingebundene Laufwerk aus der Liste aus.
  - Klicken Sie auf "Dismount", um den Container sicher zu trennen.

---

Diese Anleitung beschreibt die Schritte zur Erstellung und Verwaltung eines verschlüsselten Containers mit VeraCrypt.
