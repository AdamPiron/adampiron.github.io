# adampiron.github.io

Personal landing page of **Adam Piron** — live at **[adampiron.github.io](https://adampiron.github.io)**.

A single-page, bilingual (EN / FR) online résumé covering my background in investment banking and private equity, and the AI tools I build.

## What's on the page

| Section | Content |
| --- | --- |
| **Track Record** | M&A, Leveraged & Acquisition Finance and Private Equity experience |
| **Education** | Le Wagon (AI Product Builder), ESCP Business School, preparatory classes |
| **What I Bring** | Execution, project management, research, business development, AI automation |
| **AI Projects** | Agents, automations and apps built with Claude and Claude Code |
| **Other Experiences** | Jobs and volunteering abroad |
| **Contact** | How to get in touch, plus a downloadable CV |

## Repository structure

```
.
├── index.html                  # The whole site: markup, styles and scripts in one file
├── assets/
│   ├── CV-Adam-Piron-EN.pdf    # CV (English)
│   └── CV-Adam-Piron-FR.pdf    # CV (French)
└── README.md
```

## Tech

- **Plain HTML, CSS and JavaScript** — no framework, no build step, no dependencies
- **EN / FR language toggle** handled client-side
- **Fonts:** Cormorant Garamond and DM Sans (Google Fonts)
- **Hosting:** GitHub Pages, served from the `main` branch

## Run locally

```bash
git clone https://github.com/AdamPiron/adampiron.github.io.git
cd adampiron.github.io
open index.html
```

No server is required; opening `index.html` in a browser is enough.

## Deployment

Every push to `main` is published automatically by GitHub Pages, usually within a minute.

## Built with

Designed and iterated with [Claude](https://claude.ai), deployed with [Claude Code](https://claude.com/claude-code).
