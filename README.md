# JerriX Toys — storefront prototype

Clickable redesign of the JerriX Toys store: home, catalogue, product pages, cart, checkout, search, sign-in, contact, about and blogs.

## Run locally
Serve the folder (opening the file directly won't load scripts):

```
npx serve .
# or
python3 -m http.server
```

Then open http://localhost:8000 (or the port shown).

## Publish on GitHub Pages
1. Push this folder's contents to a repo.
2. Settings → Pages → Deploy from branch → `main` / root.
3. Keep `.nojekyll` so `.image-slots.state.json` is served.

## Structure
- `index.html` — the whole site
- `support.js` — runtime
- `image-slot.js` — image placeholders
- `.image-slots.state.json` — images placed in the editor
- `assets/` — photos, stickers, video

Blog posts are sample content. Prototype only: checkout, sign-in and contact don't send data anywhere.
