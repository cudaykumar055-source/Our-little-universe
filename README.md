# Our Little Universe — Uday & Dummy ♡

A cute pastel pink-and-white, multi-page anniversary website for GitHub Pages.

## Pages
- `index.html` — animated 3D-style gift and welcome
- `memories.html` — 8 photo slots
- `letter.html` — personal letter
- `reasons.html` — interactive reason cards
- `forever.html` — final anniversary surprise

## Music
Tap **Play music** on any page. The website creates a gentle original synthesized melody in the browser using Web Audio. No music file or copyrighted song is included. Browsers require a tap before audio can play.

## Add your real photos
The Memories page has eight preview slots. Selecting a photo previews it in that browser session only. To make photos appear for everyone on the published site:
1. Create/use `assets/photos/`.
2. Add your images there, e.g. `photo-1.jpg`, `photo-2.jpg` ...
3. Replace each photo placeholder in `memories.html` with:
   `<img src="assets/photos/photo-1.jpg" alt="Our memory" />`
   and remove the local file input/placeholder for that slot.
4. Change the captions to your own memories.

No photos were supplied with the request, so the gallery starts with empty photo frames.

## Personalize
Edit `Dummy`, captions, letter text, and reasons in the HTML files before publishing.

## Publish with GitHub Pages
1. Extract the ZIP.
2. Create a GitHub repository named `our-little-universe` (public is easiest).
3. Upload all five HTML files, `style.css`, `script.js`, and the `assets` folder to the repository root.
4. In **Settings → Pages**, choose **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Your URL will be `https://YOUR-USERNAME.github.io/our-little-universe/`.

Use relative links as provided; all pages work from the repository root.
