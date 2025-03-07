# KI-Chatbot für Schulungszwecke

Ein KI-gestützter Chatbot, der speziell für Schulungszwecke entwickelt wurde. Der Chatbot nutzt verschiedene Large Language Models (LLMs), um individuelles und zeitgemäßes Lernen zu ermöglichen. Durch die Kombination modernster KI-Technologien bietet er eine flexible und personalisierte Lernerfahrung.

## Features

- **Unterstützung durch verschiedene LLMs**: Dynamische Auswahl zwischen mehreren KI-Modellen, um spezifische Aufgaben und Fragestellungen zu bewältigen.
- **Personalisierte Lernwege**: Anpassung an den Wissensstand und die Bedürfnisse der Nutzer.
- **Unterstützung für mehrere Themenbereiche**: Von IT-Ausbildung und Programmierung bis hin zu allgemeinem Fachwissen.
- **Lokal und datenschutzfreundlich**: Der Chatbot kann lokal gehostet werden, um maximale Kontrolle über Daten zu gewährleisten.
- **Unterstützung von PDF- und Textdokumenten**: Upload und Analyse von Dokumenten, um spezifische Fragen zu beantworten.

## Einsatzmöglichkeiten

- **IT-Ausbildung**: Förderung des Lernens in technischen Berufen, z. B. Fachinformatiker (Systemintegration oder Anwendungsentwicklung).
- **Selbststudium**: Individuelle Unterstützung bei der Vorbereitung auf Prüfungen oder das Erlernen neuer Themen.
- **Klassenzimmerunterstützung**: Interaktive Lernhilfe für Schüler und Lehrer.

## Installation

### Voraussetzungen
- **Python**: Version 3.9 oder höher.
- **Abhängigkeiten**:
  - Flask (für das Webinterface)
  - PyTorch oder TensorFlow (je nach gewähltem LLM)
  - Weitere Bibliotheken (siehe `requirements.txt`)

### Schritte
1. Repository klonen:
   ```bash
   git clone https://github.com/<dein-benutzername>/ki-chatbot.git
   cd ki-chatbot
   ```
2. Abhängigkeiten installieren:
   ```bash
   pip install -r requirements.txt
   ```
3. Den Chatbot starten:
   ```bash
   python app.py
   ```
4. Öffne den Browser und greife auf das Webinterface zu unter: [http://localhost:5000](http://localhost:5000).

## Konfiguration

### Auswahl der KI-Modelle
In der Datei `config.json` kannst du die verwendeten Modelle konfigurieren. Beispiel:
```json
{
    "models": {
        "default": "gpt-3.5-turbo",
        "alternative": "open-llama",
        "local": "falcon-40b"
    },
    "fallback": "default"
}
```

### Dokumentenunterstützung aktivieren
Aktiviere die Dokumentenanalyse in der `config.json`:
```json
{
    "document_support": true
}
```

## Nutzung

1. **Fragen stellen**: Stelle einfach Fragen zu deinem Lernbereich und erhalte direkt Antworten.
2. **Dokumente hochladen**: Lade PDFs oder Textdateien hoch, um spezifische Inhalte zu erarbeiten.
3. **Lernpfad anpassen**: Wähle Themenbereiche und erhalte personalisierte Lernunterstützung.

## Beitragen
Beiträge sind willkommen! Wenn du neue Features hinzufügen oder Fehler beheben möchtest:
1. Erstelle einen Fork des Repositories.
2. Implementiere deine Änderungen.
3. Stelle einen Pull-Request.

## Lizenz
Dieses Projekt steht unter der Hammer und Sichel(LICENSE).

## Kontakt
Bei Fragen oder Feedback kannst du uns unter folgender Adresse erreichen:
- **E-Mail**: soon ya
- **GitHub Issues**:

Wir freuen uns über dein Interesse und deine Unterstützung!
