# Celestia Astrology Website

A responsive, single-page Vedic + Western astrology website starter with an animated celestial design and optional interactive 3D scene powered by Three.js.

## Run it

Because `app.js` uses JavaScript modules and dynamically imports Three.js from a CDN, run it through a local web server rather than opening `index.html` directly.

### Python
```bash
python -m http.server 8000
```
Then visit http://localhost:8000.

### VS Code
Use the Live Server extension and open `index.html`.

## Included
- Responsive homepage and mobile navigation
- Animated zodiac hero, celestial CSS effects, and Three.js 3D planets/stars when WebGL and the CDN are available
- Daily horoscope cards with Vedic-inspired and Western general reading tabs
- Vedic and Western astrology overview sections
- Date-based Western Sun-sign estimate tool
- Simple sign-element compatibility reading
- Educational astrology insight panels
- Consultation-request and newsletter demo forms with honest local-only feedback
- Accessibility support for reduced motion and basic form validation

## Important limitations
This is a functional front-end starter, not a complete production astrology service. The birth form only estimates a Western Sun sign from the date and does not calculate a full natal chart or Vedic Rashi. Accurate charts require a suitable ephemeris/calculation engine, birth coordinates, and historical time-zone handling. Horoscope content is sample content. Consultation and newsletter forms do not transmit or store data; connect a backend or provider to receive submissions. Replace any sample service details with verified business information before publishing.

Three.js is loaded from jsDelivr at runtime; an internet connection is needed for the 3D scene. CSS animations provide a fallback if it fails.
