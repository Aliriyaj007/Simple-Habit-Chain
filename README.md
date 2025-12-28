
***

# Simple Habit Chain

![Size](https://img.shields.io/github/languages/code-size/Aliriyaj007/Simple-Habit-Chain?style=flat-square&color=blue)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![Status](https://img.shields.io/badge/status-active-success?style=flat-square)
![Platform](https://img.shields.io/badge/platform-web%20%7C%20mobile%20%7C%20desktop-lightgrey?style=flat-square)

**A frictionless, offline-first habit tracker contained within a single HTML file.**

Simple Habit Chain removes the barriers between you and consistency. It requires no login, no internet connection (after loading), and no database. It is designed to be forked, customized, and used privately.

**[🚀 Launch Web App](https://aliriyaj007.github.io/Simple-Habit-Chain/)** | **[⬇️ Download Source](https://github.com/Aliriyaj007/Simple-Habit-Chain/archive/refs/heads/main.zip)**

---

## 📋 Why This Exists

Most productivity tools are over-engineered. They demand user accounts, rely on cloud synchronization, and suffer from feature bloat that distracts from the actual goal: **doing the work.**

**Simple Habit Chain** returns to basics. It utilizes the "Seinfeld Strategy" (Don't Break the Chain) in a digital format that respects your privacy and your system resources.

### The Philosophy: Zero Friction
| Feature | Standard Apps ❌ | Simple Habit Chain ✅ |
| :--- | :--- | :--- |
| **Storage** | Cloud Database (Slow) | `localStorage` (Instant) |
| **Privacy** | Data tracking/Analytics | 100% Local / Private |
| **Access** | Requires Internet | Works Offline |
| **Cost** | Subscription / Ads | Free / Open Source |
| **Codebase** | Complex Frameworks | 1 HTML File |

---

## ⚡ Features

Designed for power users who appreciate minimalism.

| Feature | Description |
| :--- | :--- |
| **Single-File Architecture** | The entire app (HTML, CSS, JS) lives in `index.html`. Portable and hackable. |
| **Visual Streaks** | Immediate visual feedback via dot-chains and heatmaps. |
| **Data Portability** | Full JSON Export/Import capabilities. You own your data. |
| **8 Custom Themes** | CSS Variable-based theming engine (Dracula, Midnight, Forest, etc.). |
| **Rich Interactions** | Confetti particles, WebAudio API success sounds, and haptic-style feedback. |
| **Responsive Grid** | CSS Grid/Flexbox layout that adapts from 4K monitors to mobile screens. |
| **Calendar Heatmap** | GitHub-contribution style view for monthly progress. |

---

## 🚀 Getting Started

You can use this tool in three ways, depending on your technical preference.

### Method 1: The Web App (Instant)
Simply visit the hosted version. Since it uses `localStorage`, your data persists in your browser.
👉 **[Click here to open](https://aliriyaj007.github.io/Simple-Habit-Chain/)**

### Method 2: Local Execution (Offline)
Run the app locally on your machine. No server required.
1. Download the `index.html` file (or the [zip archive](https://github.com/Aliriyaj007/Simple-Habit-Chain/archive/refs/heads/main.zip)).
2. Open `index.html` in any browser (Chrome, Firefox, Safari).
3. **Pro Tip:** Save it to your desktop or pin it to your mobile home screen.

### Method 3: Self-Host (Fork)
1. Fork this repository.
2. Enable **GitHub Pages** in your repository settings.
3. You now have your own instance at `your-username.github.io/Simple-Habit-Chain`.

---

## 🛠️ Usage Guide

### 1. Habit Management
*   **Add:** Type a habit name and press Enter.
*   **Track:** Click "Do it" to mark today complete. The visual chain will update.
*   **Details:** Click `...` to view the calendar heatmap and add daily notes.

### 2. Data Persistence
*   **Auto-Save:** Every action is saved immediately to the browser's LocalStorage.
*   **Backup:** Go to `Settings (Icon)` -> `Backup Data`. This downloads a `.json` file.
*   **Restore:** Go to `Settings` -> `Restore Data` and upload your JSON backup.
    *   *Note: This is useful for syncing between devices manually.*

### 3. Theming
Click the **Settings Gear** to toggle between 8 presets.
*   *Favorites:* `Midnight` (Dark Mode), `Terminal` (Hacker Green), `Classic` (Clean Blue).

---

## 👨‍💻 Technical Details

For developers interested in the source:

*   **Structure:** Monolithic HTML file. No build steps (Webpack/Vite) required.
*   **State:** Vanilla JS object state managed via a centralized `appState` variable.
*   **Audio:** Synthesized sound using the browser's `AudioContext` API (no external assets).
*   **Styling:** Pure CSS using extensive CSS Variables (`--primary`, `--bg`, etc.) for theming.

**Snippet (Theme Logic):**
```css
/* Example of how theming is handled efficiently */
[data-theme="midnight"] { 
    --bg: #0f172a; 
    --surface: #1e293b; 
    --primary: #818cf8; 
}
```

---

## 🤝 Contributing

Contributions are welcome. Since this is a single-file project, please ensure your code remains readable and dependency-free.

1.  **Fork** the project.
2.  **Create** your feature branch (`git checkout -b feature/AmazingFeature`).
3.  **Commit** your changes (`git commit -m 'Add some AmazingFeature'`).
4.  **Push** to the branch.
5.  **Open a Pull Request**.

---

## ❤️ Author & Credit

This project is maintained by **Riyajul Ali**.

*   **GitHub:** [@Aliriyaj007](https://github.com/Aliriyaj007)
*   **LinkedIn:** [Aliriyaj007](https://linkedin.com/in/Aliriyaj007)
*   **Email:** [aliriyaj007@protonmail.com](mailto:aliriyaj007@protonmail.com)

**License:** MIT. You are free to use, modify, and distribute this software.

---
*If this tool helps you maintain a streak, please consider starring the repository.* ⭐
