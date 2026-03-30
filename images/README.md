# Placeholder Images

The following images need to be added to this folder and referenced in `index.html`:

| Filename (suggested) | Section | Current Placeholder | Notes |
|---|---|---|---|
| `hero.jpg` | Hero (right column) | Green gradient, 4:5 aspect ratio | Product/arrangement photo. Update `.hero-image` with `background-image: url('images/hero.jpg'); background-size: cover;` |
| `mission.jpg` | Mission / About | Green gradient, 5:4 aspect ratio | Lobby installation or large arrangement photo. Update `.mission-image` similarly. |
| `founder.jpg` | Founder section | Green gradient, 3:4 aspect ratio | Founder portrait or arrangement detail. Update `.founder-image` similarly. |

## How to swap in real images

1. Add the image file to this `/images` folder.
2. In `index.html`, find the corresponding CSS class (noted above).
3. Replace the `background: linear-gradient(...)` with:
   ```css
   background-image: url('images/hero.jpg');
   background-size: cover;
   background-position: center;
   ```
4. Remove the `::after` pseudo-element content label if desired.
