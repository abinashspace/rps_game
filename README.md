# 🎮 Rock, Paper, Scissors — Neon UI

A single-file, browser-based Rock, Paper, Scissors game with a dark neon aesthetic, live scoring, and synthesized sound effects. Originally built as a Python/Tkinter desktop app, now rewritten for the web — no installs, no dependencies, just open it in a browser.

## 🕹️ Play

Open [`rock_paper_scissors_final.html`](./rock_paper_scissors_final.html) in any modern browser, or play it live via GitHub Pages: `https://<your-username>.github.io/<your-repo>/`

## ✨ Features

- **Classic gameplay** — Rock 🪨, Paper 📄, Scissors ✂️ against the computer
- **Neon dark theme** — glowing move buttons (green, cyan, yellow) on a dark background
- **Live scoreboard** — tracks wins, losses, and **ties**
- **Session stats** — shows total games played in the current session
- **Sound effects** — click, win, lose, and tie tones generated in-browser with the Web Audio API (no audio files required)
- **Mute toggle** — turn sound effects on/off anytime
- **Quit button** — ends the session with a farewell message

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom properties / theming)
- Vanilla JavaScript (no frameworks or libraries)
- Web Audio API for sound synthesis

## 📁 Project Structure

```
.
├── rock_paper_scissors_final.html   # The entire game (HTML + CSS + JS)
└── README.md                        # This file
```

## 🚀 Running Locally

No build step or server needed:

1. Clone or download this repository
2. Open `rock_paper_scissors_final.html` directly in your browser

## 🌐 Hosting on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under **Source**, select the `main` branch and `/ (root)` folder
4. Save — your game will be live at `https://<your-username>.github.io/<your-repo>/`

> 💡 Tip: If you want the game to load without typing the filename in the URL, rename (or duplicate) `rock_paper_scissors_final.html` to `index.html` in the repo root.

## 🎨 Color Palette

| Element         | Color     |
|-----------------|-----------|
| Background      | `#1a1b26` |
| Choice box      | `#2e2e3a` |
| Win             | `#00FF7F` |
| Lose            | `#ff355e` |
| Tie             | `#00e5ff` |
| Scissors button | `#ffe600` |

## 🔮 Possible Future Additions

- Difficulty levels (adaptive computer AI)
- Best-of-N match mode
- Win streak tracker
- Move history log
- Keyboard shortcuts (R / P / S)
- Persistent score via `localStorage`

## 📄 License

Free to use, modify, and share.
