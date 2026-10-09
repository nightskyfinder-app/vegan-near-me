# Vegan Near Me

A phone-friendly map of vegan-friendly restaurants and cafés near you.

- Uses your location, or search any city or address
- Color-coded: 100% vegan, vegan options, a few options, vegetarian
- "Open now" filter and a nearest-first list
- Tap a place for hours, address, website and directions

## Data

Restaurant info comes from [OpenStreetMap](https://www.openstreetmap.org), via the free Overpass API. Map tiles are © OpenStreetMap contributors. If a place is missing or wrong, anyone can fix it on openstreetmap.org, and the fix shows up here.

## Hosting

This is a single `index.html` file with no build step. It runs on GitHub Pages:
Settings → Pages → Deploy from a branch → `main` / `(root)`.

Location only works over https, which GitHub Pages provides.
