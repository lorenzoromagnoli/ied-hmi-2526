# IED HMI Course — Slides

Slide decks for the **Interaction Design / Automotive HMI** course, IED Master Transportation Design 2025/26.

Built with [Slidev](https://sli.dev) — Markdown source, rendered in the browser.

## Setup

Run once from this folder to install dependencies:

```bash
npm install
```

## Opening a session

Each session has its own npm script. From the `slides/` folder:

```bash
npm run s01   # Session 01 — Intro, Context & Project Brief
npm run s02   # Session 02 — Users, Tasks & HMI Architecture
npm run s03   # Session 03 — Figma Basics & Wireframes
npm run s04   # Session 04 — Flows, Components & Basic Prototypes
npm run s05   # Session 05 — Physical Controls, Arduino & ProtoPie
npm run s06   # Session 06 — Navigation Patterns & Layout
npm run s07   # Session 07 — Wireframes II: Flows & States
npm run s08   # Session 08 — Visual Language & Design System
npm run s09   # Session 09 — Applying Visual Design to Screens
npm run s10   # Session 10 — High-Fidelity Prototype & Motion
npm run s11   # Session 11 — Usability Checks & Iteration
npm run s12   # Session 12 — Refinement I
npm run s13   # Session 13 — Refinement II & Exam Prep
```

This starts a local dev server and opens the deck in your browser. Edits to the `.md` file reload live.

## Extras

```bash
npm run template      # Layout reference — all available slide templates
npm run hmi-history   # HMI history & case studies (standalone deck)
```

## Editing slides

Each session is a single Markdown file (`sNN_name.md`). Use `_template.md` as a copy-paste reference for all available layouts.
