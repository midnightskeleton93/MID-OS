```markdown
# 🖥️ Mid OS

> **A complete desktop OS — running entirely in your browser.** ✨

[![Version](https://img.shields.io/badge/version-1.1-5b8cff?style=flat-square)](https://github.com/yourname/mid-os)
[![Made with](https://img.shields.io/badge/made%20with-HTML%20%2B%20CSS%20%2B%20JS-a05bff?style=flat-square)](https://github.com/yourname/mid-os)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-0-22c55e?style=flat-square)](https://github.com/yourname/mid-os)
[![Single File](https://img.shields.io/badge/single%20file-yes-ff5b8c?style=flat-square)](https://github.com/yourname/mid-os)
[![License](https://img.shields.io/badge/license-MIT-f59e0b?style=flat-square)](LICENSE)

**Mac × Windows × Web** — all in one beautiful, self-contained HTML file.

No build step. No npm. No framework. Just open it and go. 🚀

---

## ✨ What is Mid OS?

**Mid OS** is a fully-functional desktop operating system that runs entirely in your web browser. It combines the elegance of macOS, the familiarity of Windows, and the power of the web into a single, portable HTML file.

> 🎯 **One file. Zero dependencies. Infinite possibilities.**

---

## 🎯 Features

### 🪟 Window Manager
- ✨ Smooth open/close/minimize/maximize animations
- 📌 Snap zones — drag to edges for tiling
- 🎯 Click-to-focus with z-index stacking
- 🔄 Resizable windows with corner handles
- ⌨️ Double-click title bar to maximize

### 📁 Virtual File System
- 🗂️ Persistent storage via `localStorage`
- 📂 Standard folders — Desktop, Documents, Pictures, Music, Downloads, Code
- ✏️ Create, rename, delete files and folders
- 🖼️ Image support — PNG, JPG, GIF, WebP, SVG
- 📄 Text files — Markdown, code, plain text

### 🎨 30+ Built-in Apps

| 📁 **Productivity** | 🎮 **Games** | 🛠️ **Utilities** |
|:---|:---|:---|
| 📁 Files | 🐍 Snake | 🧮 Calculator |
| 📝 Notepad | 🔢 2048 | ⌨️ Terminal |
| ✅ Todo | 🧱 Breakout | ⏱️ Stopwatch |
| 📅 Calendar | 🧩 Tetris | 📊 Task Manager |
| 📘 Markdown | ⭕ Tic-Tac-Toe | 🕐 Clock |
| 📊 Stocks | 🧠 Memory | 🌤️ Weather |
| 💻 Code Editor | 💣 Minesweeper | 📷 Camera |
| 🎨 Paint | 🔢 Sudoku | ⚙️ Settings |

| 🌐 **Media & Web** | 🤖 **AI** |
|:---|:---|
| 🌐 Browser | 🌙 Midnight AI (chat) |
| 🎵 Music Player | |
| 🖼️ Image Viewer | |
| 🎬 Video Player | |

### 🧩 Widgets
Drag-and-drop widgets on your desktop:
- 🕐 Clock · 🌤️ Weather · ✅ Tasks · 📅 Calendar
- 📝 Notes · 📊 System Info · 💬 Quote · 🧮 Calculator · 📈 Market

### 👥 Multi-User
- 🔐 Multiple user accounts with isolated files
- 🔒 Optional password protection
- 🎭 Custom display names & avatars

### 🎨 Customization
- 🖼️ 10 wallpapers + upload your own
- 🎨 8 accent colors — the whole OS recolors
- 📱 3 view modes — Desktop, Tablet, Mobile
- 🌙 Glassmorphism UI with beautiful blur & transparency

### 🌐 Web App Integration
- ➕ Add any website as a desktop app
- 📌 Pin shortcuts in start menu
- 🚀 Launch with one click

---

## 🖱️ Desktop Icon System

Icons live on a **fixed invisible grid**. This keeps your desktop tidy:

- 🎯 Auto-snap — icons align perfectly to grid cells
- 🚫 No overlap — one icon per cell
- ✥ Move mode — right-click → "Move icon…" → drag → release to snap
- 🔄 Auto-fill — new icons fill the first available cell
- ✨ Reset — right-click desktop → "Reset icon positions"

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|:---|:---|
| `Ctrl` + `Space` | 🎯 Open Start Menu |
| `Ctrl` + `T` | ⌨️ Open Terminal |
| `Ctrl` + `E` | 📁 Open Files |
| `Ctrl` + `L` | 🔒 Lock Screen |
| `Ctrl` + `Z` / `Y` | ↩️ Undo / Redo (Paint) |
| `Escape` | ❌ Close menus / cancel move |
| `Double-click` | 🖱️ Open icon / maximize window |

---

## 🚀 Quick Start

### 🌟 Just open it
1. 📥 Download `index.html`
2. 🖱️ Double-click the file — it opens in your browser
3. 🎉 Welcome to Mid OS!

### 🌐 Serve locally
```bash
python -m http.server 8000
# or
npx serve
```

Then visit 👉 http://localhost:8000

🔧 Deploy

Works instantly on GitHub Pages, Netlify, Vercel, Cloudflare Pages — just upload index.html.

---

🛠️ Tech Stack

Layer Tech
🧱 Structure Pure HTML5
🎨 Styling Vanilla CSS3 (glassmorphism, flexbox, grid)
⚡ Logic Vanilla JavaScript (ES6+)
💾 Storage localStorage + IndexedDB (music)
🎵 Audio Web Audio API + HTML5 <audio>
📷 Camera getUserMedia API
🌤️ Weather Open-Meteo (free, no key)
🌐 Browser iframe + r.jina.ai (reader mode)

No frameworks. No bundlers. No build step. Just clean, readable, hackable code.

---

🗺️ Roadmap

🎯 v1.2

☐ 🎨 Dock — macOS-style magnifying dock
☐ 🔍 Spotlight Search (Ctrl+Space)
☐ 🔔 Notification Center + quick toggles
☐ 🎭 Light theme toggle
☐ 🔊 System sounds

🚀 v1.3

☐ 🖥️ Multi-desktop / workspaces
☐ 📋 Clipboard manager
☐ ✂️ Screen snip tool
☐ 📂 File drag & drop between windows
☐ ⌨️ Window snap shortcuts

🌟 v2.0

☐ 📱 PWA support (install as real app)
☐ ☁️ Cloud sync (export/import)
☐ 📸 Photos app
☐ 🗺️ Maps integration
☐ 📖 PDF reader

---

🤝 Contributing

Contributions are welcome! 🎉

```bash
git clone https://github.com/yourname/mid-os.git
cd mid-os
# Open index.html in your browser
# Make changes
# Submit a PR
```

Ideas: 🐛 Report bugs · 💡 Suggest features · 🎨 Build new apps · 📝 Improve docs

---

📜 License

Released under the MIT License — free to use, modify, and distribute.

---

<div align="center">

⭐ If you like Mid OS, give it a star! ⭐

Built with 💙 and a lot of position: fixed

</div>
```
