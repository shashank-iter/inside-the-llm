# Inside the LLM — A Visual Journey

An interactive, scroll-driven explainer that visualises every step of how a Large Language Model processes a question and generates an answer. Built for curious minds — no PhD required.

## 🌐 Live Demo
[inside-the-llm.netlify.app](https://inside-the-llm.netlify.app) <!-- replace with your actual URL -->

## 📖 What It Covers

| Step | Concept |
|------|---------|
| 01 | Tokenisation |
| 02 | Embeddings |
| 03 | Positional Encoding |
| 04 | Self-Attention |
| 05 | Vectors in 3D Space |
| 06 | Feed-Forward Layers |
| 07 | Logits & Probabilities |
| 08 | Temperature & Sampling |
| 09 | Autoregressive Generation |

## ✨ Features

- **Scroll-driven animations** — each concept reveals as you scroll
- **Interactive temperature slider** — see how output changes from deterministic to chaotic in real time
- **3D vector space** — drag and rotate token embeddings rendered in WebGL
- **Attention heatmap** — switch between attention heads and hover cells to inspect scores
- **3 sample questions** — trace any of the three questions through the entire pipeline
- **Dark mode** — enabled by default, toggleable
- **Fully responsive** — works on mobile and desktop

## 🛠 Tech Stack

- Vanilla HTML, CSS, JavaScript — single file, zero build step
- [Tailwind CSS](https://tailwindcss.com) via CDN
- [Chart.js](https://www.chartjs.org) — bar, line, and scatter charts
- [Three.js](https://threejs.org) — 3D token vector space
- [GSAP + ScrollTrigger](https://greensock.com/gsap) — scroll animations
- [Google Fonts](https://fonts.google.com) — DM Serif Display, JetBrains Mono, Outfit

## 🚀 Getting Started

No installation needed. Just open the file in a browser:

```bash
git clone https://github.com/shashank-iter/inside-the-llm
cd inside-the-llm
open index.html
```

Or drag `index.html` directly into any browser.
