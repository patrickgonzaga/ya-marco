# Ya Marco! Chili Garlic

A one-page 3D scroll website for Ya Marco homemade chili garlic.

- Live WebGL fire shader, a 3D jar and cartoon garlic/chili characters built with [three.js](https://threejs.org) (loaded from jsDelivr)
- The jar and characters move between sections as you scroll; the fire flares up in the Heat Level section
- Order builder: visitors build an order message and copy it to send to you

## Files
- `index.html` contains the whole site (HTML, CSS and JS)
- `yamarco-logo.svg` is the logo
- `assets/` holds the kitchen videos and product photos

## Run locally
Any static server works, for example:

```bash
npx serve .
```

## Deploy
Static site with no build step. On Vercel, the framework preset is "Other" and the output directory is the repo root.
