# Frans Lungile Plumbers — Draft Preview (MOE Media)

Single-file draft site: `index.html`. No build step. Deploy as a static site (Vercel / GitHub Pages).

## What it is
A **pitch preview** for a warm lead (Frans replied 5 Nov 2026 asking for a link). It must look premium but clearly read as a draft:
- Striped "DRAFT PREVIEW" bar with a **Hide notes / Show notes** toggle
- Yellow handwritten-style sticky-note bubbles (①–⑤) explaining each section
- Image slots labelled "Photo: …" where his real job photos will go
- Animations: flowing-water pipe SVG in hero, pulsing "available now" dot, count-up stats, scroll reveal, hover lift on cards
- `noindex,nofollow` so Google never lists it

## Facts used (verified)
- Phone / WhatsApp: 063 379 9184 (+27633799184)
- Rating: 4.9 on Google, 66 reviews; open 24 hours
- Location: Rietfontein, Hartbeespoort
- Services from Procompare + reviews: geysers, leak detection, pumps/tanks, blocked drains, bathroom installs
- His Procompare profile is unclaimed (pitch point)

## Rules — do not break
- **No fake reviews.** Review slots stay as placeholders until Frans approves using his real Google reviews.
- **Keep the draft banner + footer credit** while this is a preview. It must never pass as his official site.
- Service-area suburbs are a guess — confirm with Frans.

## Tasks for Claude Code
1. Create repo `frans-plumbing-preview`, commit `index.html`.
2. Add 4–5 **free-licence** stock photos (Unsplash or Pexels: plumber at work, geyser, leak repair, bathroom) into the `.slot` divs and as the hero background (`.hero-img`, keep the dark gradient overlay). Download into `/img`, compress to WebP < 200 KB, credit photographers in a footer line. Keep the "Photo: …" labels — they show it's a stand-in.
3. Deploy to Vercel → `frans-plumbing-preview.vercel.app`.
4. Test on a phone: call + WhatsApp buttons, bottom floating bar, notes toggle.

## Message to send Frans with the link
> Hi Frans, here's a draft preview of your website: [link]
> The yellow notes explain each part. Tap "Hide notes" to see it clean. Once we work on it together, we'll add your real photos, reviews and logo.
> For an example of a finished site I've built, have a look at redbatch.store.
> The full site is R3,500. Want to jump on a quick call to go through it?
