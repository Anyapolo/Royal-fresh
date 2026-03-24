# Royal Fresh Events

A single-page marketing website for **Royal Fresh Events** — a premium fruits and vegetables supplier for the events industry. 20+ years on the market, direct sourcing, same-day delivery.

## Project Structure

```
royal-fresh/
├── index.html        # Main (and only) page — HTML + CSS in one file
└── images/
    └── arrangement.jpg   # Hero/about section image
```

## Tech Stack

- Plain HTML & CSS — no frameworks, no build tools
- Fonts via Google Fonts: Playfair Display, IBM Plex Mono, IBM Plex Sans
- Fully responsive: mobile, tablet (640px+), desktop (1024px+)

## Sections

- **Hero** — full-screen background with headline and CTA
- **Who We Serve** — horizontal strip listing target clients
- **Inspiration** — event styling ideas and use cases
- **Catalog** — filterable product grid (fruits & vegetables)
- **Why Fresh** — freshness guarantee list
- **How We Work** — 4-step process
- **About** — company story + stats (20+ years, 0 middlemen, same-day delivery)
- **Contact CTA** — bottom call to action
- **Footer** — copyright + location

## Contact Popup

Clicking any CTA button opens a slide-up contact popup with links to:
- Telegram: [@daniileg](https://t.me/daniileg)
- WhatsApp: +7 988 348 81 88
- Phone call

## Deployment

Hosted as a static site. To deploy:

```bash
git init
git add .
git commit -m "initial commit"
git remote add origin https://github.com/Anyapolo/Royal-fresh.git
git branch -M main
git push -u origin main
```

Then connect the repo to [Render](https://render.com) as a Static Site, or enable GitHub Pages under repo Settings → Pages.

## Local Development

No build step needed. Just open `index.html` in a browser — or use VS Code's Live Server extension for auto-reload.

## Stylesheet Reference

### Fonts

| Font | Weights | Usage |
|------|---------|-------|
| Playfair Display | 400, 600, italic | Headings, section titles, numbers |
| IBM Plex Mono | 400, 500 | Labels, tags, nav, buttons, footer |
| IBM Plex Sans | 300, 400, 500 | Body text, descriptions |

### Colours

| Variable | Hex | Usage |
|----------|-----|-------|
| `--bg` | `#E6E5D1` | Page background |
| `--text` | `#080F0F` | Primary text, borders |
| `--accent-yellow` | `#EAEC87` | Highlight backgrounds, CTA sections |
| `--accent-green` | `#417B5A` | Who strip, footer, hover states |
| `--accent-orange` | `#FF7D0D` | Process step numbers |
| `--border` | `1px solid #080F0F` | Strong borders |
| `--border-light` | `1px solid rgba(8,15,15,0.15)` | Subtle dividers |

