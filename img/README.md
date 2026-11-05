# Photo slots

Drop WebP files (< 200 KB each) here with these exact names; the page picks them up automatically.
Missing files are skipped gracefully (the illustrated placeholder shows instead).

| File            | Where it shows                       | Suggested size |
|-----------------|--------------------------------------|----------------|
| `hero.webp`     | Hero circle (square crop, subject centred) | 1000 × 1000 |
| `about-1.webp`  | "Why Frans" collage, large photo      | 900 × 1000     |
| `about-2.webp`  | "Why Frans" collage, small close-up   | 600 × 680      |
| `geyser.webp`   | Services card: Geysers               | 600 × 500      |
| `leak.webp`     | Services card: Leak detection        | 600 × 500      |
| `pump.webp`     | Services card: Pumps & tanks         | 600 × 500      |
| `bathroom.webp` | Services card: Drains & bathrooms    | 600 × 500      |

Convert: `python3 -c "from PIL import Image; im=Image.open('in.jpg'); im.thumbnail((1920,1920)); im.save('hero.webp', quality=72)"`

Then credit the photographers in the `PHOTO-CREDITS` comment in the footer of `index.html`.
