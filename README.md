# AlphaTrack Digital — Static Pages

This repo contains static, Tailwind-CDN pages ready for free hosting (Netlify / Vercel / GitHub Pages / Cloudflare Pages).

## Pages
- `index.html` — Conversion Tracking
- `services.html` — Services Grid
- `marketing-automation.html` — Marketing Automation
- `book-call.html` — Book a Strategy Call (replace iframe URL)
- `thank-you.html` — Thank you / confirmation

## Assets
- `assets/logo.png` — included (placeholder from provided logos)
- `assets/roobert.woff2` — add your licensed Roobert font here
  - A placeholder note is provided: `assets/ROOBERT_PLACEHOLDER.txt`

## Local preview
Open any HTML file directly, or run a simple static server:

```bash
python -m http.server 8080
# then open http://localhost:8080
```

## Deploy (Netlify)
Drag-and-drop the folder, or connect the GitHub repo and deploy as a static site.

## Deploy (GitHub Pages)
1. Create a repo and push these files
2. In GitHub: Settings → Pages → Deploy from branch → select `main` / root
