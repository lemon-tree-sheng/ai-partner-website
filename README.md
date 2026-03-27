# AI Partner Website — 不米文化 BUMI

> 停止追赶 AI，建立你自己的 AI 操作系统  
> Stop Chasing AI. Build Your AI Operating System.

## Tech Stack

- HTML + Tailwind CSS (no framework, zero bloat)
- Bilingual ZH/EN with JS language toggle
- Auto-deploy to GitHub Pages via GitHub Actions

## Local Dev

```bash
npm install
npm run dev   # watch mode, rebuilds CSS on change
```

Open `src/index.html` in browser (use Live Server or similar).

## Deploy

Every push to `main` triggers GitHub Actions → builds CSS → deploys to GitHub Pages automatically.

## Structure

```
ai-partner-website/
├── src/
│   ├── index.html       ← Main landing page (bilingual)
│   ├── input.css        ← Tailwind directives
│   └── dist/
│       └── output.css   ← Generated (gitignored, built by CI)
├── tailwind.config.js
├── package.json
└── .github/
    └── workflows/
        └── deploy.yml   ← Auto-deploy on push to main
```

## Content Sections

1. **Hero** — Core value proposition
2. **Pain** — 3 types of AI anxiety
3. **Insight** — The AI Laziness Paradox + 5 capabilities
4. **Solution** — What is an AI OS (4 layers)
5. **Products** — 3-tier: Newsletter (free) / Course (¥399) / 1:1 Workshop (¥5999)
6. **About** — Sheng's story
7. **Newsletter CTA** — Email subscribe

---

*不米文化咨询有限公司 © 2026*
