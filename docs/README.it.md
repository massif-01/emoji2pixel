# 🎨 Emoji2Pixel

Trasforma emoji e immagini in splendide opere di pixel art con questo potente convertitore web. Crea animazioni stupefacenti, personalizza ogni dettaglio ed esporta le tue creazioni come immagini o GIF.

![Emoji2Pixel Badge](https://img.shields.io/badge/Emoji2Pixel-v1.0-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Languages](https://img.shields.io/badge/languages-8-orange)

## ✨ Funzionalità

### 🖼️ **Input Multi-Sorgente**
- **Supporto Emoji**: Inserisci emoji direttamente o sfoglia una libreria completa
- **Importazione Immagini**: Carica qualsiasi file immagine per la pixelizzazione
- **Modalità Auto-Fit**: Regola automaticamente la scala dell'emoji per adattarsi perfettamente alla tela
- **Ricerca e Filtro**: Ricerca rapida di emoji con navigazione per categorie

### 🎬 **Sistema di Animazione**
- **Animazione Keyframe**: Crea animazioni fluide con più keyframe
- **Interpolazione Tween**: Generazione automatica di frame di transizione tra keyframe
- **Controlli di Riproduzione**: Riproduci, pausa e regola la velocità dell'animazione in tempo reale
- **Esportazione GIF**: Esporta animazioni come file GIF animati

### 🎛️ **Controlli di Trasformazione Avanzati**
- **Scala**: Ridimensiona la tua opera d'arte dallo 0% al 200%
- **Posizione**: Regola con precisione l'offset X/Y per un allineamento perfetto
- **Rotazione**: Ruota in qualsiasi direzione (0-360°)
- **Tela Interattiva**: Manipolazione diretta con clic e trascinamento + Tieni premuto Shift per ruotare

### 🎨 **Potente Motore di Rendering**
- **Due Modalità di Rendering**:
  - **Modalità Ideale**: Pixel art professionale con spazi e bordi personalizzabili
  - **Modalità Bare**: Rendering pixel puro per uno stile retrò autentico
- **Tela Flessibile**: Dimensione griglia regolabile (da 8x8 a 128x128 pixel)
- **Stili di Pixel**: Scegli tra pixel quadrati, arrotondati o circolari
- **Quantizzazione del Colore**: Riduci la palette di colori a 2-256 colori per un'estetica retrò
- **Filtri di Nitidezza**: Migliora la definizione dei bordi con intensità regolabile

### 🖌️ **Strumenti di Modifica**
- **Rimozione Sfondo**: Rimozione intelligente dello sfondo con controllo della tolleranza
- **Strumenti di Selezione**: Selezione rettangolare con riempimento, cancellazione, copia e incolla
- **Sistema di Livelli**: Flusso di lavoro di editing non distruttivo
- **Supporto Annulla**: Annulla operazioni di selezione colore e rimozione sfondo

### 📏 **Opzioni di Esportazione Professionale**
- **Unità Multiple**: Lavora in millimetri, pollici o unità di griglia
- **Preset Dimensioni**: Preset rapidi per dimensioni di display comuni
- **Formati di Esportazione**:
  - PNG (con trasparenza)
  - GIF (animato o statico)
  - Dati pixel grezzi
- **Rendering Frame**: Visualizza il layout fisico dei pixel con dimensioni reali

### 🌍 **Supporto Internazionale**
Traduzioni integrate per 8 lingue:
- 🇨🇳 简体中文 (Cinese semplificato)
- 🇺🇸 English (Inglese)
- 🇫🇷 Français (Francese)
- 🇩🇪 Deutsch (Tedesco)
- 🇮🇹 Italiano
- 🇯🇵 日本語 (Giapponese)
- 🇰🇷 한국어 (Coreano)
- 🇪🇸 Español (Spagnolo)

## 🚀 Avvio Rapido

### Demo Online
Visita la demo live: [https://thomas-hiddenpeak.github.io/emoji2pixel](https://thomas-hiddenpeak.github.io/emoji2pixel)

### Sviluppo Locale

1. **Clona il repository**
   ```bash
   git clone https://github.com/thomas-hiddenpeak/emoji2pixel.git
   cd emoji2pixel
   ```

2. **Servire localmente**
   
   Usando Python:
   ```bash
   python -m http.server 8000
   ```
   
   O usando Node.js:
   ```bash
   npx http-server -p 8000
   ```

3. **Apri nel browser**
   ```
   http://localhost:8000
   ```

Nessun processo di build richiesto! Questa è un'applicazione web statica pura.

## 📖 Guida all'Uso

### Flusso di Lavoro Base

1. **Input**: Inserisci un emoji o carica un'immagine
2. **Trasforma**: Regola scala, posizione e rotazione a tuo piacimento
3. **Aggiungi Frame**: Clicca il pulsante `+` per aggiungere alla tua animazione
4. **Personalizza**: Modifica le impostazioni di rendering, stile pixel e colori
5. **Esporta**: Scarica come PNG o GIF

### Scorciatoie da Tastiera

| Scorciatoia | Azione |
|-------------|--------|
| `Spazio` | Attiva/disattiva riproduzione animazione |
| `Invio` | Aggiungi vista corrente come keyframe |
| `Canc` / `Backspace` | Elimina frame selezionato |
| `←` / `→` | Naviga tra i frame |
| `Esc` | Annulla selezione/selezione colore |
| `Ctrl/Cmd + C` | Copia selezione |
| `Ctrl/Cmd + V` | Incolla selezione |

### Suggerimenti Pro

- 🎯 **Tieni premuto Shift** mentre trascini sulla tela per ruotare invece di spostare
- 🔍 Usa la **Quantizzazione del Colore** (8-64 colori) per pixel art retrò autentica
- ⚡ Abilita la **Nitidezza** (30-50% di intensità) per migliorare la chiarezza dei bordi
- 🎬 Imposta i **Frame Tween** su 5-10 per animazioni fluide
- 📐 Usa la **Modalità Rendering Frame** per visualizzare layout di matrici LED fisiche

## 🛠️ Stack Tecnologico

- **Frontend Puro**: HTML5, CSS3, JavaScript Vanilla
- **Nessuna Dipendenza**: Zero librerie o framework esterni
- **API Canvas**: Manipolazione pixel ad alte prestazioni
- **GIF.js**: Codifica GIF lato client
- **Design Responsive**: Funziona su dispositivi desktop e tablet

## 📁 Struttura del Progetto

```
emoji2pixel/
├── index.html          # Struttura HTML principale
├── app.js              # Logica applicazione principale
├── styles.css          # Stile e layout
├── locales/            # Internazionalizzazione
│   ├── index.json      # Manifesto delle lingue
│   ├── it-IT.json      # Traduzioni italiane
│   ├── en-US.json      # Traduzioni inglesi
│   └── ...             # Altre lingue
├── docs/               # Documentazione multilingue
│   ├── README.it.md    # Documentazione italiana
│   ├── README.en.md    # Documentazione inglese
│   └── ...             # Altre lingue
└── scripts/            # Utilità di build
    └── generate_locales_index.py
```

## 🌐 Aggiungere Nuove Lingue

1. Crea un nuovo file lingua in `locales/` (es. `pt-BR.json`)
2. Copia la struttura da un file lingua esistente
3. Traduci tutte le chiavi nella tua lingua target
4. Aggiungi un campo `selfName` con un emoji bandiera
5. Esegui il generatore di indice delle lingue:
   ```bash
   python scripts/generate_locales_index.py
   ```

La nuova lingua apparirà automaticamente nel selettore lingue!

## 🤝 Contribuire

I contributi sono benvenuti! Ecco come puoi aiutare:

- 🐛 Segnala bug e problemi
- 💡 Suggerisci nuove funzionalità
- 🌍 Aggiungi o migliora le traduzioni
- 📝 Migliora la documentazione
- 🎨 Invia showcase di pixel art

### Linee Guida di Sviluppo

1. Forka il repository
2. Crea un branch per la funzionalità (`git checkout -b feature/amazing-feature`)
3. Committa le tue modifiche (`git commit -m 'Add amazing feature'`)
4. Pusha al branch (`git push origin feature/amazing-feature`)
5. Apri una Pull Request

## 📄 Licenza

Questo progetto è concesso in licenza con la Licenza MIT - vedi il file [LICENSE](../LICENSE) per i dettagli.

## 🙏 Ringraziamenti

- Dati emoji provenienti dagli standard Unicode
- Ispirato da strumenti di pixel art classici e display a matrice LED
- Realizzato con ❤️ per la comunità pixel art

## 📮 Contatto e Supporto

- **Problemi**: [GitHub Issues](https://github.com/thomas-hiddenpeak/emoji2pixel/issues)
- **Discussioni**: [GitHub Discussions](https://github.com/thomas-hiddenpeak/emoji2pixel/discussions)

---

<div align="center">

**Realizzato con 🎨 e ⌨️**

Se trovi utile questo progetto, considera di dargli una ⭐!

[English](README.en.md) | [简体中文](README.zh-CN.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md)

</div>
