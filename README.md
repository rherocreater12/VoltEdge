# VoltEdge — website (v2, with Founder sect ion)

Static single-page site for VoltEdge's product suite (Shakti, Vidyut, Variq, Sol, Dhara, Path) plus a Founder section for Yashwant Atre.

## Deploy on GitHub Pages
1. Push the contents of this folder (`index.html`, `support.js`, `image-slot.js`, `images/`) to a GitHub repo.
2. Settings → Pages → set source to the branch/root you pushed to.
3. Live at `https://<username>.github.io/<repo>/`.

## Images
- `images/` holds the product dashboard screenshots — replace any file to update that section's image.
- The Founder photo is a drag-and-drop slot in the page itself (not a static file) — open `index.html` in a browser and drop a photo onto it; it persists in a `.image-slots.state.json` sidecar next to the HTML. If you'd rather use a static file, swap the `<x-import component-from-global-scope="image-slot" ...>` block for a plain `<img src="images/founder.jpg">`.

## Editing
Everything is in `index.html`, inline-styled — open it and search for the text you want to change.
