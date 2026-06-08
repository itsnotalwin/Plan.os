# Repo Work Tracker OS

> A personal execution command center for managing GitHub repositories, projects, ideas, and development workflows.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Vanilla JS](https://img.shields.io/badge/JS-Vanilla-lightgrey)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-0-brightgreen)
![PWA Ready](https://img.shields.io/badge/PWA-Ready-blue)
![Offline First](https://img.shields.io/badge/Offline-Ready-green)

Repo Work Tracker OS is a lightweight, offline-first personal operating system for software projects. It's **not** a GitHub analytics dashboard or a repository viewer. It's built to help you **decide what to work on next**, maintain visibility across active projects, and capture ideas before they become repos.

Built with zero frameworks, zero backends, and zero external APIs. Everything runs in your browser and persists locally.

---

## 🖼️ Screenshots

*(Replace these placeholders with actual screenshots after deployment)*

![Dashboard](https://via.placeholder.com/800x450/111111/333333?text=Dashboard+Preview)
*Clean, information-dense dashboard with smart highlighting for blocked, overdue, and stale projects.*

![Workspace](https://via.placeholder.com/800x450/111111/333333?text=Project+Workspace)
*Full project workspace with drag-and-drop Kanban, milestones, build logs, and dev journal.*

---

## ✨ Features

- **🎯 Execution-Focused Dashboard** – Information-dense project grid with visually dominant "Next Action" fields
- **📊 Smart Highlighting** – Automatically surfaces blocked, overdue, and stale (7+ days) projects
- **🗂️ Project Workspaces** – Kanban task boards (drag & drop), milestones, build logs, dev journals, and reference links
- **💡 Ideas Database** – Capture concepts and promote them to full projects with one click
- **📚 Knowledge Database** – Personal engineering wiki for snippets, deployment notes, and lessons learned
- **🌗 Dark & Light Themes** – Persistent toggle with smooth transitions
- **⌨️ Keyboard-Driven** – Full shortcut support for navigation, creation, and theme toggling
- **📦 Import/Export** – Full JSON backup and restore for all collections
- **📱 PWA & Offline-First** – Installable on desktop/mobile, works completely offline after first load
- **🖥️ Desktop-First, Responsive** – Optimized for wide screens with intelligent mobile adaptation
- **🔒 100% Local** – No servers, no APIs, no tracking. All data stays in your browser's `localStorage`
- **🧩 Zero Dependencies** – Pure HTML, CSS, and vanilla JavaScript. No build step required.

---

## 🚀 Quick Start

1. **Clone or download** this repository
2. Open `index.html` in any modern browser
3. That's it. No installation, no build step, no configuration.

### 🌐 Deploy to GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Select your branch (e.g., `main`) and `/ (root)` folder
4. Click **Save**
5. Your app will be live at `https://<username>.github.io/<repo-name>/`

*The app is fully self-contained in a single `index.html` file. No additional build or server configuration is needed.*

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `N` | New Project |
| `/` | Focus Search |
| `Esc` | Close Modal / Go Back |
| `B` | Toggle Sidebar |
| `T` | Toggle Dark/Light Theme |
| `G` then `D` | Go to Dashboard |
| `G` then `I` | Go to Ideas |
| `G` then `K` | Go to Knowledge |
| `G` then `A` | Go to Activity Log |
| `?` | Show Shortcuts |
| `Ctrl + E` | Export Data |

---

## 🔒 Data & Privacy

- **100% Client-Side**: All data is stored in your browser's `localStorage`. Nothing is sent to any server.
- **Backup & Restore**: Use the export feature (`Ctrl+E` or sidebar → Export) to download a full JSON backup. Import it anytime on any device.
- **No Tracking**: Zero analytics, zero cookies, zero external requests (except Google Fonts, which can be removed if desired).
- **Storage Limits**: `localStorage` typically holds ~5–10MB per origin. This is enough for thousands of projects, tasks, and notes. Use Export/Import for long-term archives.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|------------|
| Structure | Semantic HTML5 |
| Styling | CSS3 (Custom Properties, Flexbox, Grid, Responsive) |
| Logic | Vanilla JavaScript (ES5+ compatible) |
| Persistence | `localStorage` (wrapped in safe try/catch layer) |
| Icons | Canvas API (dynamically generated PWA icons & favicons) |
| Offline | Service Worker (gracefully degrades if Blob SW isn't supported) |
| Fonts | Inter & JetBrains Mono (with system fallbacks) |

---

## 📝 Notes & Customization

- **Starter Ideas**: 12 curated project ideas are automatically injected on load if missing. Delete or promote them as needed.
- **Remove Google Fonts**: Delete the two `<link>` tags in `<head>`. The CSS will automatically fall back to system sans-serif/monospace fonts.
- **Theme Persistence**: Theme preference is saved to `localStorage` and applied instantly on reload.
- **Drag & Drop**: Native HTML5 drag-and-drop for task columns. Works on desktop; mobile users can edit task status via the edit modal.

---

## 🤝 Contributing

This is a personal productivity tool, but contributions are welcome! Feel free to open issues or submit PRs for:
- Bug fixes & edge-case handling
- Performance & accessibility improvements
- Features that align with the **execution-first, zero-dependency** philosophy

Please keep the codebase vanilla, dependency-free, and under a single HTML file.

---

## 📄 License

MIT License. See `LICENSE` for details.

---
Built for developers who ship. 🚀
