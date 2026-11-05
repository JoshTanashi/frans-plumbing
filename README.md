# Frans Lungile Plumbers — draft preview (MOE Media)

Single-file static pitch site: `index.html`. No build step. Deployed on Vercel (project `frans-plumbing-preview`); every push to `main` redeploys.

- `img/` — photo slots (see `img/README.md`). Missing photos fall back to placeholders.
- `vercel.json` / `robots.txt` — keep the preview out of search engines.
- `HANDOVER.md` — brief, facts used, and rules (no fake reviews, keep the draft banner).

## Design
Light layout with yellow (`#f6b800`) and teal (`#0e5e66`) accents. Fonts (Outfit, Inter, Caveat; SIL OFL) are self-hosted in `fonts/`.
Until real photos are added, the photo slots show illustrated stand-ins.

## Share images
- `og.jpg`: 1200×630 link preview (WhatsApp/Facebook show it when the URL is shared)
- `promo/frans-preview-card.png`: 1120×1440 portrait card for sending on WhatsApp/socials
