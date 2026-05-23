# Interaction Design · Automotive HMI
**IED Master Transportation Design · 2025/26**  
Lorenzo Romagnoli — 14 sessions · May – September 2026

---

## Folder structure

```
/
├── admin/              # Student data, attendance register (private, not in git)
├── source-materials/   # Reference docs, ICS calendar, old slides (private, not in git)
├── publish/
│   └── index.html      # Course landing page → lorenzoromagnoli.github.io/ied-hmi-2526
└── slides/             # Slidev source — one .md file per session
```

## Working on slides locally

```bash
cd slides
npm install          # first time only

npm run s01          # open S01 in the browser with hot reload
npm run s02          # same for any other session
```

Each session file maps to a script in `slides/package.json`.

## Publishing to GitHub Pages

Deployment is **fully manual** — you decide when each session goes live.

1. Go to the repo on GitHub → **Actions** → **Deploy** → **Run workflow**
2. Pick what to deploy from the dropdown:

| Option | What happens |
|---|---|
| `s01 — Intro…` … `s13 — …` | Builds that one deck and updates the index page |
| `index` | Updates only the landing page (no rebuild) |
| `all` | Builds all 13 decks and updates the index page |

Already-published sessions are never touched when deploying a single deck.  
Build time: ~2 min per session, ~15 min for `all`.

**Live URL:** `https://lorenzoromagnoli.github.io/ied-hmi-2526`

## What is and isn't in git

| Path | In repo | Reason |
|---|---|---|
| `slides/` | ✅ | Source code and assets |
| `publish/` | ✅ | Course index page |
| `admin/` | ❌ | Contains student personal data |
| `source-materials/` | ❌ | Local reference material only |
| `slides/node_modules/` | ❌ | Installed locally via `npm install` |
| `slides/dist/` | ❌ | Built by CI, deployed to gh-pages branch |
