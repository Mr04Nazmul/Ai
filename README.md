# SA-BR Nutzora — 3D boutique

A buildless Bengali storefront for Mini Honey Nuts (20g) and Nut Mix (18g).

## Run

Serve `dist/` with any static HTTP server. No build or API key is required. The Three.js 0.180.0 modules are vendored locally.

## Experience

- Interactive real-time 3D showroom, drag to look, keyboard/touch walking, product hotspots, home reset and fullscreen.
- Accessible HTML product catalog even when WebGL is unavailable.
- Browser-local cart; quantity pricing per product: 10–50 at BDT 20; 51–100 at BDT 16.5; 101+ at BDT 16.
- Each box includes one free spoon. Delivery fee is confirmed by the business.
- WhatsApp order composition; no message is sent automatically, and there is no payment processing or server-side order storage.
- The showroom and pack models are illustrative, not a measured reconstruction of a physical store. Real product photographs were not downloaded because the source required Facebook sign-in.

## Attribution

Animated navigation links adapted to vanilla HTML/CSS from Skiper UI's free Skiper40 Link000 by @gurvinder-singh02, https://skiper-ui.com/r/skiper40.json (personal/commercial adaptation allowed, attribution retained on the site). Product-card hover treatment is independently implemented, inspired by Aceternity UI's 3D Card Effect, https://ui.aceternity.com/components/3d-card-effect. No paid component source was used.

Three.js is MIT licensed; see `dist/assets/THREE-LICENSE.txt`. Brand name, product details and business contact were supplied by the owner and its public Facebook page.
