# AI/ML Engineer Portfolio — 2025

An interactive **Three.js portfolio** with a floating 3D particle field background, markdown-rendered project descriptions, and smooth scroll-driven navigation.

**[▶ Live Demo](https://woodyhoko.github.io/portfolio_2025)**

---

## Features

- 🌌 **WebGL particle background** — Three.js particle system responding to cursor movement
- 📝 **Markdown rendering** — project descriptions parsed and sanitized via marked.js + DOMPurify
- 🎨 **Dark gradient theme** — green-to-blue headline gradients, glass-card sections
- 📱 **Responsive** — adapts from mobile to ultrawide
- ⚡ **No build tools** — single HTML file, all deps from CDN

---

## Stack

| Library | Purpose |
|---|---|
| [Three.js r128](https://threejs.org/) | 3D particle field |
| [marked.js](https://marked.js.org/) | Markdown → HTML |
| [DOMPurify](https://github.com/cure53/DOMPurify) | XSS sanitization |
| Tailwind-style custom CSS | Layout & theming |

---

## Run Locally

```bash
python -m http.server 8000
# open http://localhost:8000
```

