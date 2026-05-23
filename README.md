# Interaction Design · Automotive HMI
**IED Master Transportation Design · 2025/26**  
Lorenzo Romagnoli — 14 sessions · May – September 2026

---

## Folder structure

```
/
├── admin/              # Student data, attendance register (private, not in git)
├── source-materials/   # Reference docs, ICS calendar, old slides (private, not in git)
├── docs/               # Built output → served by GitHub Pages
│   │                   # (name is fixed — GitHub Pages only supports /docs)
│   ├── index.html      # Course landing page
│   ├── s01/            # Built S01 slides (created by npm run build:s01)
│   └── …
└── slides/             # Slidev source — one .md file per session
```

**Live URL:** `https://lorenzoromagnoli.github.io/ied-hmi-2526`

---

## Working on slides locally

```bash
cd slides
npm install          # first time only

npm run s01          # open S01 in the browser with hot reload
npm run s02          # same for any other session
```

---

## Publishing a session

Build locally, then commit and push — GitHub Pages serves the `docs/` folder directly.

```bash
cd slides

# Build one session
npm run build:s01

# Or rebuild everything
npm run build:all
```

Then publish:

```bash
git add ../docs
git commit -m "publish S01"
git push
```

The site updates within seconds of the push.

---

## What is and isn't in git

| Path | In repo | Reason |
|---|---|---|
| `slides/` | ✅ | Source code and assets |
| `docs/` | ✅ | Built output served by GitHub Pages |
| `admin/` | ❌ | Contains student personal data |
| `source-materials/` | ❌ | Local reference material only |
| `slides/node_modules/` | ❌ | Installed locally via `npm install` |
