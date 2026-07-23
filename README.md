# Lighthouse Samui

Informational website for **Lighthouse Samui** — a licensed cannabis store at Malibu Resort, Bo Put, Koh Samui, Thailand.

The site is informational only: it presents the store, opening hours, location, and a reference guide to cultivars. It is **not** an advertisement or an offer to sell, and it carries no prices and no online or delivery ordering. Entry is age-gated to adults 20+.

## Structure

- `index.html` — the full single-page site (self-contained: HTML + CSS + a little JS, no build step, no dependencies).

## Local preview

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Hosted on **Cloudflare Pages**, connected to this GitHub repo. Any push to `main` triggers a deploy.

- Build command: _(none)_
- Build output directory: `/` (repo root)
- Production branch: `main`

Custom domain: `lighthousekohsamui.com`
