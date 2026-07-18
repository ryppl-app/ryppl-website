# Ryppl — Marketing website

A lightweight, static site for **Ryppl**, the AI wellness companion. No build step, no framework, no images — plain HTML + one shared stylesheet, using the app's palette (teal `#0B6E6E`, bg `#EBF5F5`, area colours) and fonts (Plus Jakarta Sans + DM Sans).

## Pages
| File | Purpose |
|---|---|
| `index.html` | Landing — hero, "companion not tracker", the three focus areas, privacy, CTA. |
| `contact.html` | Simple contact / early-access form + `contact@ryppl.app`. |
| `styles.css` | Shared, trimmed design system (responsive). |

## Run locally
Static — open `index.html`, or:
```bash
python3 -m http.server 8000   # → http://localhost:8000
```

## Before launch (TODO)
- **Wire the contact form** — front-end only right now (shows a thank-you, stores nothing). Point it at a form service (Formspree/Basin) or the backend, or rely on `contact@ryppl.app`.
- Add real Privacy / Terms pages (footer links are placeholders).

## Deploy
Static hosting — S3 + CloudFront, Netlify, Vercel, or GitHub Pages. Point `ryppl.app` at it.

_© Ryppl 2026 — Small ripples. Whole life._
