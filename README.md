# Unit 2 Netter Practical — Study Guide

A self-contained, single-page timed lab-practical simulator for the Unit 2 anatomy lab ID list
(Netter's *Clinical Anatomy*, 4th ed.).

**Live site:** https://jthorne27.github.io/unit2-netter-practical/

## What it does

- **Pin practical mode** — timed stations, random plates, typed answers, scoring.
- **Browse plates** — all 75 labeled plates with every Unit 2 structure pinned; tap a pin to reveal its name.
- Covers 346 structures across head & face, neck, back, thorax, anterior/posterior abdominal wall, and deep pelvis.
- Works offline once loaded, on phone or laptop, light and dark mode.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The entire app — markup, styles, data, and every plate image (base64) in one ~7.9 MB file. No build step, no dependencies. |
| `.nojekyll` | Tells GitHub Pages to serve files as-is instead of running Jekyll. |

## Updating the site

Replace `index.html` with a new export and push:

```bash
git add index.html
git commit -m "Update plates"
git push
```

GitHub Pages redeploys automatically in about a minute.

## Content note

Plate images are from *Netter's Clinical Anatomy*, 4th ed., reproduced here for classroom study only.
