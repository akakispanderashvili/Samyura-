# Samkura Bio Farm website

A simple static website for **Samkura Bio Farm (სამყურა)** in Tsnori, Kakheti, Georgia.
It has plain HTML, CSS and a little JavaScript, and needs no build step.

## Structure
```
index.html              Home: hero, product cards, sweet-potato section, why bio, journal, contact
articles/               Journal articles (sweet potatoes, why bio, seasonal eating)
css/style.css           All styles. Colours and fonts are set at the top (:root)
js/main.js              Mobile menu, product filter, scroll animations
images/photos/          Photos (WebP), from Wikimedia Commons for now
credits.html            Photo credits, required by the photo licences
```

## Open it locally
Double-click `index.html`, or run `python3 -m http.server` and visit http://localhost:8000.

## Things to replace
Search for `REPLACE` in the files.
- Phone number (`tel:` link in index.html)
- The product list and seasons (confirm with the farm)
- The farming practices in "What bio means", which must be true for this farm
- The farmer quote in `articles/sweet-potato.html`
- Photos: the current ones are free stock photos from Wikimedia Commons. Swap in the farm's own photos with the same file names in `images/photos/`, then remove those rows from `credits.html`

## Put it online (free)
**GitHub Pages:** go to repo Settings → Pages → Deploy from branch → choose the branch and the `/ (root)` folder.
**Netlify / Cloudflare Pages:** drag and drop the folder, or connect this repo.
