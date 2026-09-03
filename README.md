# Lyzr Emerging Partners — Rapid Prototyping Workshop

Static landing page for the Lyzr Emerging Partners: Rapid Prototyping Workshop (September 15).

## Structure

- `index.html` — the full page (inline CSS + JS, no build step)
- `assets/hero-speaker.png` — hero speaker artwork
- `.nojekyll` — serve files as-is on GitHub Pages

Fonts come from Google Fonts; GSAP/ScrollTrigger and Lenis load from CDN.

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploy

GitHub Pages → Settings → Pages → Source: `main` branch, `/ (root)`.
