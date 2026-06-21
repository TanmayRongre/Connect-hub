# 🔗 Connect Hub — Personal Link Hub

> A custom-built Linktree-style link aggregator with a dark glassmorphism UI. All your important links in one place. Built with vanilla HTML, CSS & JavaScript.

🌐 **Live:** [tanmayrongre.github.io/Connect-hub](https://tanmayrongre.github.io/Connect-hub)

---

## ✨ Features

- 🎨 **Dark glassmorphism UI** — matching design language with the portfolio
- 🖱️ **Custom animated cursor** — dot + trailing outline with hover effects (desktop only)
- 🪟 **Glassmorphic link tiles** — each link is a blurred, bordered card with hover lift animation
- 👤 **Profile section** — avatar with gradient ring, username, and bio
- 🔗 **5 quick-access links** — Resume, Portfolio, GitHub, LinkedIn, LeetCode
- 📱 **Fully responsive** — works cleanly on mobile & desktop
- ⚡ **Zero dependencies** — pure HTML, CSS & JS

---

## 🗂️ Project Structure

```
Connect Hub/
├── index.html       # Single-page layout with profile + link tiles
├── style.css        # All styles, design tokens, cursor & responsive rules
├── script.js        # Custom cursor with touch-device detection
└── icons/
    ├── profile.png      # Profile photo
    ├── resume.png       # Resume tile icon
    ├── portfolio.png    # Portfolio tile icon
    ├── github.png       # GitHub tile icon
    ├── linkedin.png     # LinkedIn tile icon
    └── leetcode.png     # LeetCode tile icon
```

---

## 🛠️ Tech Stack

| Layer     | Technology              |
|-----------|-------------------------|
| Structure | HTML5 (semantic)        |
| Styling   | Vanilla CSS3            |
| Logic     | Vanilla JavaScript      |
| Fonts     | Google Fonts — Poppins  |
| Hosting   | GitHub Pages            |

---

## 🔗 Links Included

| Tile        | Destination |
|-------------|-------------|
| 📄 Resume   | Google Drive (PDF) |
| 🌐 Portfolio | [tanmayrongre.qzz.io](https://tanmayrongre.qzz.io) |
| 🐙 GitHub   | [github.com/TanmayRongre](https://github.com/TanmayRongre) |
| 💼 LinkedIn | [linkedin.com/in/tanmayrongre](https://linkedin.com/in/tanmayrongre) |
| 🧩 LeetCode | [leetcode.com/u/oz1gZ2yoGB](https://leetcode.com/u/oz1gZ2yoGB/) |

---

## 🖱️ Custom Cursor

The custom cursor is **desktop-only**. On touch / mobile devices it automatically falls back to the native browser cursor:

```css
@media (hover: none) and (pointer: coarse) {
    *, *:before, *:after { cursor: auto !important; }
    .cursor-dot, .cursor-outline { display: none !important; }
}
```

---

## 🚀 Getting Started

No build step needed — just open in a browser:

```bash
# Clone the repo
git clone https://github.com/TanmayRongre/Connect-hub.git

# Open locally
cd Connect-hub
start index.html      # Windows
open index.html       # macOS
```

Or visit the live site: **[tanmayrongre.github.io/Connect-hub](https://tanmayrongre.github.io/Connect-hub)**

---

## 🔗 More Links

- 🌐 **Portfolio** — [tanmayrongre.qzz.io](https://tanmayrongre.qzz.io)
- 💼 **LinkedIn** — [linkedin.com/in/tanmayrongre](https://linkedin.com/in/tanmayrongre)
- 🐙 **GitHub** — [github.com/TanmayRongre](https://github.com/TanmayRongre)

---

## 📄 License

© 2026 Tanmay Rongre. All rights reserved.

---

<p align="center">Engineered by <strong>Tanmay Rongre</strong></p>
