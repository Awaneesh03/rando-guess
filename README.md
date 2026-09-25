<div align="center">

# 🕵️ Case Assignment Ceremony

**A cinematic, crime-noir web app that randomly assigns "case files" to participants — with scanning effects, glitch text and a generated soundtrack.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Web Audio API](https://img.shields.io/badge/Web_Audio_API-333333?style=flat-square)

</div>

---

## 📖 About

Built for a classroom / event activity: each participant enters their name and the app "investigates" before revealing a randomly drawn case (number + title). A case is never handed out twice, so everyone gets a unique assignment — and the reveal feels like an event rather than a spreadsheet.

## ✨ Features

- 🎲 **Fair random assignment** — each case is drawn from the remaining pool, no duplicates
- 🗂️ **Case database** — add, delete or clear cases; everything is saved in `localStorage`
- 🔁 **Remembers assignments** — the same name always gets the same case back; reset any time
- 🎬 **Cinematic reveal** — scanning messages, glitch-text decoding and a screen flash
- 🌫️ **Atmosphere** — canvas particles, drifting fog, scanlines, crime-scene tape and a graveyard skyline
- 🎵 **Procedural soundtrack** — a noir background score synthesised live with the **Web Audio API** (no audio files)

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| UI | HTML5, CSS3 (animations, gradients, clip-paths) |
| Logic | Vanilla JavaScript |
| Graphics | HTML Canvas |
| Audio | Web Audio API (oscillators, filters, delay) |
| Storage | `localStorage` |
| Dev server / build | [Vite](https://vitejs.dev) |

Everything lives in a single [`index.html`](index.html) — no framework and no runtime dependencies.

## 🚀 Getting Started

```bash
git clone https://github.com/Awaneesh03/rando-guess.git
cd rando-guess
npm install
npm run dev        # → http://localhost:5173
```

Build a static version for hosting:

```bash
npm run build      # outputs to dist/
npm run preview
```

## 🎮 How to Use

1. Open the app and enter a participant's name.
2. Watch the investigation sequence reveal their case.
3. Manage the list of cases from the case panel (add / delete / clear).
4. Use **reset** to start a fresh ceremony.

---

## 👤 Author

**Awaneesh Gupta** — B.Tech CSE (AI) @ Vedam School of Technology

[![GitHub](https://img.shields.io/badge/GitHub-Awaneesh03-181717?style=flat-square&logo=github)](https://github.com/Awaneesh03)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-awaneesh--gupta-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/awaneesh-gupta)

<p align="center"><sub>If you found this project useful, consider giving it a ⭐</sub></p>
