# Vedic Astrology — Three-Format Reference Chart

A static, browser-only reference chart for GitHub Pages.

## Files
- `index.html` — complete application (HTML, CSS and JavaScript in one file).

## Run locally
Open a terminal in this folder and run:
```bash
python3 -m http.server 8000
```
Then visit `http://localhost:8000`.

Opening via `file://` may behave differently across browsers; use a local HTTP server or GitHub Pages.

## Publish on GitHub Pages
1. Upload `index.html` and this README to your repository.
2. Enable GitHub Pages from the repository's Settings → Pages.
3. Select the branch and folder containing `index.html`.
4. Open the published Pages URL.

## Included
- 360° zodiac wheel with 12 sign sectors and 108 selectable pada segments.
- North Indian and South Indian chart views.
- Selectable lagna for house/sign mapping.
- Seven-planet selector embedded in each right-side description panel.
- North Indian chart labels placed within individual house regions.
- South Indian fixed-sign layout arranged in anticlockwise zodiac order, beginning with Aries at the top-left and Taurus down the left edge.
- Eight descriptive reference sections and pada boundary table.
- Responsive layout and print stylesheet.
- No external libraries, images, APIs, or server-side dependencies.

## Important conventions
- The traditional dignity table for the seven planets includes exaltation, debilitation and moolatrikona degrees.
- Rahu/Ketu exaltation and debilitation differ across Jyotish traditions; the app shows the common Taurus/Scorpio scheme and identifies the Gemini/Sagittarius alternative.
- The house/sign classification lists in section 8 follow the user's supplied scheme. The fruitfulness and dual-sign lists overlap as supplied.
- Pada's sign is calculated from the midpoint of its 3°20′ interval. Boundary endpoints are displayed in zodiac degrees.

Created for the community — Swapnil Karambelkar.
