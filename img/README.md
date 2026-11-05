# Photo slots

Drop WebP files (< 200 KB each) here with these exact names; the page picks them up automatically.
Missing files are skipped gracefully (the emoji / gradient placeholder shows instead).

| File            | Where it shows                       | Suggested size |
|-----------------|--------------------------------------|----------------|
| `hero.webp`     | Hero background (under dark overlay) | 1920 × 1080    |
| `geyser.webp`   | Services card: Geysers               | 800 × 540      |
| `leak.webp`     | Services card: Leak detection        | 800 × 540      |
| `pump.webp`     | Services card: Pumps & tanks         | 800 × 540      |
| `bathroom.webp` | Services card: Drains & bathrooms    | 800 × 540      |

Convert: `python3 -c "from PIL import Image; im=Image.open('in.jpg'); im.thumbnail((1920,1920)); im.save('hero.webp', quality=72)"`

Then credit the photographers in the `PHOTO-CREDITS` comment in the footer of `index.html`.
