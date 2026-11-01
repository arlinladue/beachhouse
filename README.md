# The Beach House Exmouth

Static site, served by GitHub Pages from the root of `main`:
https://new.thebeachhouseexmouth.co.uk (www is back on the old Scrumpy site since 2026-11-01)

- `index.html` is the whole site (template plus logic), rendered in the browser by `support.js`.
- `location-maps.html` is the embedded Leaflet map.
- `images/full/` holds the photos (max 1600px) and `images/thumb/` the gallery thumbnails (max 640px).

To preview locally: `python3 -m http.server 8765`, then open http://localhost:8765.
