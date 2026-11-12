# Gizem Akdağ Portfolio Style

A reverse-engineered design specification, assets, and AI prompt for building an ultra-clean, poetic portfolio inspired by [gizemakdag.com](https://gizemakdag.com/).

## Overview

- **Single-page static portfolio** with zero build tools (`index.html`, `style.css`, `app.js`).
- **Stage**: Full-screen 1456×816 ultramarine (`#34428a`) portrait canvas (`images/portrait.webp`).
- **Teardrop animation**: Two live teardrops mask project covers using organic water drop alpha silhouettes (`images/tear1.png`, `images/tear2.png`), holding and falling with custom easing curves.
- **Circular clip-path transition**: Interactive sheets (Projects, Index, Store, Info) expand in a circle from the click center and contract back on close.
- **Typography**: Instrument Serif (display) + DM Mono (UI & labels) via local webfonts (`fonts/`).
- **Tone & Palette**: Ultramarine (`#34428a`), cream (`#f4e8e1`), lip crimson (`#b3141e`), skin blush (`#e9b9a6`).

## Directory Structure

```
├── AGENTS.md       # Implementation rules for AI agents
├── PROMPT.md       # Master generation prompt
├── content/        # Baseline structured data (site.json, projects.json, store.json)
├── fonts/          # Instrument Serif & DM Mono webfonts + fonts.css
├── images/         # Portrait canvas, teardrop alpha masks & favicons
└── uploads/        # Sample project media & collab videos
```

## Quick Start (Agent / Developer)

To pull baseline assets directly into your workspace:

```bash
curl -sL https://github.com/joejojoking-cloud/gizem-akdag-prompt/archive/main.tar.gz | tar -xz --strip-components=1
```

Or reference remote assets via jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/joejojoking-cloud/gizem-akdag-prompt@main/
```
