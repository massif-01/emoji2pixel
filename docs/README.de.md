# 🎨 Emoji2Pixel

Verwandeln Sie Emojis und Bilder mit diesem leistungsstarken webbasierten Konverter in wunderschöne Pixel-Art. Erstellen Sie atemberaubende Animationen, passen Sie jedes Detail an und exportieren Sie Ihre Kreationen als Bilder oder GIFs.

![Emoji2Pixel Badge](https://img.shields.io/badge/Emoji2Pixel-v1.0-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Languages](https://img.shields.io/badge/languages-8-orange)

## ✨ Funktionen

### 🖼️ **Mehrere Eingabequellen**
- **Emoji-Unterstützung**: Geben Sie Emojis direkt ein oder durchsuchen Sie eine umfassende Emoji-Bibliothek
- **Bildimport**: Laden Sie beliebige Bilddateien zur Pixelierung hoch
- **Auto-Anpassungsmodus**: Passt die Emoji-Skalierung automatisch an, um perfekt in die Leinwand zu passen
- **Suche & Filter**: Schnelle Emoji-Suche mit Kategorienavigation

### 🎬 **Animationssystem**
- **Keyframe-Animation**: Erstellen Sie flüssige Animationen mit mehreren Keyframes
- **Tween-Interpolation**: Automatische Generierung von Übergangsbildern zwischen Keyframes
- **Wiedergabesteuerung**: Abspielen, Pausieren und Anpassen der Animationsgeschwindigkeit in Echtzeit
- **GIF-Export**: Exportieren Sie Animationen als animierte GIF-Dateien

### 🎛️ **Erweiterte Transformationssteuerung**
- **Skalierung**: Ändern Sie die Größe Ihres Kunstwerks von 0% bis 200%
- **Position**: Feinabstimmung des X/Y-Versatzes für perfekte Ausrichtung
- **Drehung**: Drehen Sie in jede Richtung (0-360°)
- **Interaktive Leinwand**: Direkte Manipulation mit Klicken & Ziehen + Shift-Taste gedrückt halten zum Drehen

### 🎨 **Leistungsstarke Rendering-Engine**
- **Zwei Render-Modi**:
  - **Idealer Modus**: Professionelle Pixel-Art mit anpassbaren Abständen und Rändern
  - **Bare-Modus**: Reines Pixel-Rendering für authentischen Retro-Stil
- **Flexible Leinwand**: Einstellbare Rastergröße (8x8 bis 128x128 Pixel)
- **Pixel-Stile**: Wählen Sie zwischen quadratischen, abgerundeten oder kreisförmigen Pixeln
- **Farbquantisierung**: Reduzieren Sie die Farbpalette auf 2-256 Farben für Retro-Ästhetik
- **Schärfungsfilter**: Verbessern Sie die Kantendefinition mit einstellbarer Stärke

### 🖌️ **Bearbeitungswerkzeuge**
- **Hintergrundentfernung**: Intelligente Hintergrundentfernung mit Toleranzkontrolle
- **Auswahlwerkzeuge**: Rechteckige Auswahl mit Füllen, Löschen, Kopieren & Einfügen
- **Ebenensystem**: Nicht-destruktiver Bearbeitungsworkflow
- **Rückgängig-Unterstützung**: Machen Sie Farbauswahl- und Hintergrundentfernungsoperationen rückgängig

### 📏 **Professionelle Exportoptionen**
- **Mehrere Einheiten**: Arbeiten Sie in Millimetern, Zoll oder Rastereinheiten
- **Größenvorlagen**: Schnelle Vorlagen für gängige Displaygrößen
- **Exportformate**:
  - PNG (mit Transparenz)
  - GIF (animiert oder statisch)
  - Rohe Pixeldaten
- **Frame-Rendering**: Visualisieren Sie das physische Pixel-Layout mit realen Abmessungen

### 🌍 **Internationale Unterstützung**
Integrierte Übersetzungen für 8 Sprachen:
- 🇨🇳 简体中文 (Vereinfachtes Chinesisch)
- 🇺🇸 English (Englisch)
- 🇫🇷 Français (Französisch)
- 🇩🇪 Deutsch
- 🇮🇹 Italiano (Italienisch)
- 🇯🇵 日本語 (Japanisch)
- 🇰🇷 한국어 (Koreanisch)
- 🇪🇸 Español (Spanisch)

## 🚀 Schnellstart

### Online-Demo
Besuchen Sie die Live-Demo: [https://thomas-hiddenpeak.github.io/emoji2pixel](https://thomas-hiddenpeak.github.io/emoji2pixel)

### Lokale Entwicklung

1. **Repository klonen**
   ```bash
   git clone https://github.com/thomas-hiddenpeak/emoji2pixel.git
   cd emoji2pixel
   ```

2. **Lokal bereitstellen**
   
   Mit Python:
   ```bash
   python -m http.server 8000
   ```
   
   Oder mit Node.js:
   ```bash
   npx http-server -p 8000
   ```

3. **Im Browser öffnen**
   ```
   http://localhost:8000
   ```

Kein Build-Prozess erforderlich! Dies ist eine reine statische Webanwendung.

## 📖 Benutzerhandbuch

### Grundlegender Workflow

1. **Eingabe**: Geben Sie ein Emoji ein oder laden Sie ein Bild hoch
2. **Transformation**: Passen Sie Skalierung, Position und Drehung nach Belieben an
3. **Frame hinzufügen**: Klicken Sie auf die Schaltfläche `+`, um zu Ihrer Animation hinzuzufügen
4. **Anpassen**: Optimieren Sie Render-Einstellungen, Pixel-Stil und Farben
5. **Exportieren**: Als PNG oder GIF herunterladen

### Tastaturkürzel

| Tastenkürzel | Aktion |
|--------------|--------|
| `Leertaste` | Animationswiedergabe umschalten |
| `Enter` | Aktuelle Ansicht als Keyframe hinzufügen |
| `Entf` / `Rücktaste` | Ausgewählten Frame löschen |
| `←` / `→` | Zwischen Frames navigieren |
| `Esc` | Auswahl/Farbauswahl abbrechen |
| `Strg/Cmd + C` | Auswahl kopieren |
| `Strg/Cmd + V` | Auswahl einfügen |

### Profi-Tipps

- 🎯 **Shift-Taste gedrückt halten** beim Ziehen auf der Leinwand zum Drehen statt Bewegen
- 🔍 Verwenden Sie **Farbquantisierung** (8-64 Farben) für authentische Retro-Pixel-Art
- ⚡ Aktivieren Sie **Schärfung** (30-50% Stärke) zur Verbesserung der Kantenklarheit
- 🎬 Setzen Sie **Tween-Frames** auf 5-10 für flüssige Animationen
- 📐 Verwenden Sie den **Frame-Render-Modus** zur Visualisierung physischer LED-Matrix-Layouts

## 🛠️ Technischer Stack

- **Reines Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Keine Abhängigkeiten**: Null externe Bibliotheken oder Frameworks
- **Canvas API**: Hochleistungs-Pixelmanipulation
- **GIF.js**: Clientseitige GIF-Kodierung
- **Responsive Design**: Funktioniert auf Desktop- und Tablet-Geräten

## 📁 Projektstruktur

```
emoji2pixel/
├── index.html          # Haupt-HTML-Struktur
├── app.js              # Kern-Anwendungslogik
├── styles.css          # Styling und Layout
├── locales/            # Internationalisierung
│   ├── index.json      # Sprachen-Manifest
│   ├── de-DE.json      # Deutsche Übersetzungen
│   ├── en-US.json      # Englische Übersetzungen
│   └── ...             # Andere Sprachen
├── docs/               # Mehrsprachige Dokumentation
│   ├── README.de.md    # Deutsche Dokumentation
│   ├── README.en.md    # Englische Dokumentation
│   └── ...             # Andere Sprachen
└── scripts/            # Build-Utilities
    └── generate_locales_index.py
```

## 🌐 Neue Sprachen hinzufügen

1. Erstellen Sie eine neue Sprachdatei in `locales/` (z.B. `pt-BR.json`)
2. Kopieren Sie die Struktur aus einer vorhandenen Sprachdatei
3. Übersetzen Sie alle Schlüssel in Ihre Zielsprache
4. Fügen Sie ein `selfName`-Feld mit einem Flaggen-Emoji hinzu
5. Führen Sie den Sprachen-Index-Generator aus:
   ```bash
   python scripts/generate_locales_index.py
   ```

Die neue Sprache erscheint automatisch im Sprachselektor!

## 🤝 Mitwirken

Beiträge sind willkommen! So können Sie helfen:

- 🐛 Bugs und Probleme melden
- 💡 Neue Funktionen vorschlagen
- 🌍 Übersetzungen hinzufügen oder verbessern
- 📝 Dokumentation verbessern
- 🎨 Pixel-Art-Showcases einreichen

### Entwicklungsrichtlinien

1. Forken Sie das Repository
2. Erstellen Sie einen Feature-Branch (`git checkout -b feature/amazing-feature`)
3. Committen Sie Ihre Änderungen (`git commit -m 'Add amazing feature'`)
4. Pushen Sie zum Branch (`git push origin feature/amazing-feature`)
5. Öffnen Sie einen Pull Request

## 📄 Lizenz

Dieses Projekt ist unter der MIT-Lizenz lizenziert - siehe [LICENSE](../LICENSE)-Datei für Details.

## 🙏 Danksagungen

- Emoji-Daten aus Unicode-Standards
- Inspiriert von klassischen Pixel-Art-Tools und LED-Matrix-Displays
- Mit ❤️ für die Pixel-Art-Community entwickelt

## 📮 Kontakt & Support

- **Probleme**: [GitHub Issues](https://github.com/thomas-hiddenpeak/emoji2pixel/issues)
- **Diskussionen**: [GitHub Discussions](https://github.com/thomas-hiddenpeak/emoji2pixel/discussions)

---

<div align="center">

**Mit 🎨 und ⌨️ gemacht**

Wenn Sie dieses Projekt nützlich finden, geben Sie ihm bitte einen ⭐!

[English](README.en.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Italiano](README.it.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md)

</div>
