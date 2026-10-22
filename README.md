# Canine Style

A complete, responsive, image-free single-page website for a Sydney dog fashion and accessories store.

## Files

- `index.html` — semantic page structure, navigation, full article, responsive contact form, and lightweight interactions.
- `style.css` — all visual design, gradients, CSS-only artwork, responsive breakpoints, hover states, animation, and reduced-motion handling.
- `manus-routes.json` — managed preview route declaration.
- `package.json` — optional local preview command.
- `app.config.ts` — managed project logo metadata.

## Preview locally

From this folder, run:

```bash
python3 -m http.server 3000
```

Then open `http://localhost:3000`.

The contact form is intentionally front-end only and shows a confirmation state without sending data to a server. Replace the submit handler with the form service of your choice when you are ready to connect enquiries.
