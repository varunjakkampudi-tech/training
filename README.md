# 📚 Tech Learning Library

A complete, self-contained **study & interview-prep library** of 14 in-depth technical guides — covering frontend, backend, web & APIs, and cloud/DevOps. Every guide is a single responsive HTML file with a searchable sidebar, copy-to-clipboard code blocks, real-world scenarios, and interview Q&A.

🔗 **Live site:** https://varunjakkampudi-tech.github.io/training/

---

## 🌐 Guides

| # | Guide | Category | Highlights |
|---|-------|----------|-----------|
| 1 | [JavaScript](https://varunjakkampudi-tech.github.io/training/javascript.html) | Frontend | Core language, async, closures, event loop |
| 2 | [React](https://varunjakkampudi-tech.github.io/training/react.html) | Frontend | Hooks, context, Router (loaders/actions), auth |
| 3 | [Material UI](https://varunjakkampudi-tech.github.io/training/materialui.html) | Frontend | Theming, components, styling patterns |
| 4 | [MongoDB](https://varunjakkampudi-tech.github.io/training/mongodb.html) | Backend | Gold-standard guide — CRUD, aggregation, indexing, design |
| 5 | [Node.js](https://varunjakkampudi-tech.github.io/training/nodejs.html) | Backend | Event loop, streams, V8/GC, production architecture |
| 6 | [Express.js](https://varunjakkampudi-tech.github.io/training/expressjs.html) | Backend | Middleware, lifecycle, streaming, resilience |
| 7 | [FastAPI](https://varunjakkampudi-tech.github.io/training/fastapi.html) | Backend | Async, Pydantic, dependency injection |
| 8 | [REST API](https://varunjakkampudi-tech.github.io/training/restapi.html) | Web & APIs | HTTP internals, conditional requests, webhooks |
| 9 | [SEO](https://varunjakkampudi-tech.github.io/training/seo.html) | Web & APIs | Technical SEO, Core Web Vitals, structured data |
| 10 | [Accessibility](https://varunjakkampudi-tech.github.io/training/accessibility.html) | Web & APIs | WCAG, ARIA, keyboard & screen-reader support |
| 11 | [Cross-Browser](https://varunjakkampudi-tech.github.io/training/crossbrowser.html) | Web & APIs | Compatibility, feature detection, testing |
| 12 | [AWS](https://varunjakkampudi-tech.github.io/training/aws.html) | Cloud & DevOps | 12 modules + hands-on Lambda & API Gateway serverless |
| 13 | [Linux Administration](https://varunjakkampudi-tech.github.io/training/linux.html) | Cloud & DevOps | Permissions, systemd, networking, scripting, hardening |
| 14 | [Docker](https://varunjakkampudi-tech.github.io/training/docker.html) | Cloud & DevOps | Multi-stage builds, Compose, React/FastAPI/Express |

---

## ✨ Features

- **📱 Fully responsive** — works on desktop, tablet, and mobile (collapsible sidebar, reflowing grids, horizontally scrollable code/diagrams).
- **🔎 Searchable sidebar** — filter topics instantly within each guide.
- **📋 Copy-to-clipboard** code blocks with syntax highlighting.
- **🌍 Real-world scenarios** and hands-on labs, not just theory.
- **❓ Interview Q&A** and scenario questions in every guide.
- **🎨 Distinct theme** per guide for quick visual recognition.
- **⚡ Zero build step** — pure HTML/CSS/JS, hosted free on GitHub Pages.

---

## 🚀 Running Locally

No dependencies or build tools are required — just open the files in a browser:

```bash
# Clone
git clone https://github.com/varunjakkampudi-tech/training.git
cd training

# Open the library hub
start index.html      # Windows
# open index.html     # macOS
# xdg-open index.html # Linux
```

Or serve it with any static server:

```bash
npx serve .
# then visit http://localhost:3000
```

---

## 📂 Structure

```
index.html          # Library hub (links to all guides)
javascript.html     # Frontend guides
react.html
materialui.html
mongodb.html        # Backend guides
nodejs.html
expressjs.html
fastapi.html
restapi.html        # Web & APIs guides
seo.html
accessibility.html
crossbrowser.html
aws.html            # Cloud & DevOps guides
linux.html
docker.html
README.md
```

---

## 🛠️ Tech

Plain **HTML + CSS + vanilla JavaScript** — each guide is fully self-contained (no external dependencies, no frameworks, no build). Deployed via **GitHub Pages** from the `main` branch.

---

_Built as a comprehensive study & interview resource. Contributions and suggestions welcome._
