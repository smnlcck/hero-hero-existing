# hero-existing

A replica of the current [simonalcock.ie](https://simonalcock.ie) homepage hero, rebuilt as a baseline for the section-by-section homepage redesign. Other hero variants will be compared against it.

Measured from the live site at 1440 × 900:

- Five role tabs (For everyone, Design Leaders, UX & Product Designers, Product Managers, Developers)
- Full-bleed portrait background on a rounded card inside the 25px page frame
- Animated scroll prompt

The only content change from the live site is the "For Developers" tab, which now uses valid CSS syntax.

Open `index.html` in a browser to view it.

## Fonts

Eudoxus Sans Medium and Aeonik Fono Regular are licensed fonts, so they are not in this repo. The page loads them from simonalcock.ie. Browsers only allow that if simonalcock.ie sends an `Access-Control-Allow-Origin` header for its font files; without it, the text falls back to Helvetica.
