# 🧠 KarteiKraft

**Interactive German vocabulary learning app (DE→PT-BR)**

Built for Brazilian Portuguese speakers learning German, based on the official **Goethe-Zertifikat A2 and B1** word lists.

🔗 **[Abrir o App →](https://lucasmatturro-art.github.io/karteikraft/)**

---

## 📸 Overview

Choose your level (A2 or B1), then practice with 4 different activities:

| Activity | Description |
|----------|-------------|
| 📚 **Flashcards** | Flip cards with TTS audio and speech recognition |
| 🦆 **Entenjagd** | Duck hunt — shoot the duck with the correct translation |
| 🧠 **Memória** | Memory matching game — find DE↔PT pairs |
| 🔗 **Conectar** | Draw lines connecting words to their translations |

---

## 📊 Vocabulary

| Level | Nouns | Verbs | Total |
|-------|-------|-------|-------|
| A2 — Elementar | 508 | 223 | **731** |
| B1 — Intermediário | 270 | 193 | **463** |
| **Total** | **778** | **416** | **1.194** |

All words extracted from the official Goethe-Institut certification word lists.

### Gender Color System
- 🔵 **Azul** — der (masculine)
- 🔴 **Vermelho** — die (feminine)
- 🟢 **Verde** — das (neuter)
- ⚫ **Cinza** — Verbs

---

## 🚀 How to Use

### Online (recommended)
Visit the GitHub Pages link above. On Android, tap the browser menu → **"Install app"** to add it to your home screen.

### Offline
1. Download `index.html`
2. Open in any modern browser
3. Requires internet only on first load (for React CDN)

---

## 🛠 Tech Stack

- **React 18** via CDN (single-file, no build step)
- **Babel** for JSX compilation in-browser
- **Web Speech API** — Text-to-Speech (de-DE) + Speech Recognition
- **SVG** — Hand-drawn duck illustrations, Bézier connection lines
- **Fonts** — Gaegu (hand-drawn) + DM Sans (UI)

---

## 📱 Install as PWA (Android)

1. Open the app in **Chrome**
2. Tap **⋮** menu → **"Install app"** or **"Add to Home screen"**
3. The app opens fullscreen like a native app

---

## 📂 Project Structure

```
├── index.html          # The entire app (single file)
├── README.md
└── LICENSE
```

---

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or submit PRs. Some ideas:

- [ ] Add A1 level vocabulary
- [ ] Expand B1 word list (currently ~460 of ~1300 words)
- [ ] Add progress tracking with localStorage
- [ ] Service Worker for full offline support
- [ ] Sound effects for games
- [ ] Dark/light theme toggle

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

## 🙏 Credits

- Vocabulary sourced from [Goethe-Institut](https://www.goethe.de/) official A2/B1 Wortliste
- Built with [Claude](https://claude.ai) by Anthropic
