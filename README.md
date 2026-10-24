# SA-BR Nutzora — 3D boutique

A multi-page, animated Bengali storefront for Mini Honey Nuts (20g) and Nut Mix (18g).

## Run

Serve `dist/` with any static HTTP server. No build or API key is required. The Three.js 0.180.0 modules are vendored locally.

## Experience

Home, Shop, 3D Store, Honey Nuts, Nut Mix, Wholesale and Our Story are separate static pages. Includes catalog filtering/search, a two-image honey gallery and live quantity quotes. The immersive dark-green and amber stage supports drag, walking and product hotspots.

- Interactive real-time 3D showroom, drag to look, keyboard/touch walking, product hotspots, home reset and fullscreen.
- Compact supermarket showroom with grocery gondolas, illuminated shelf-edge tickets, linear lights and a checkout counter. CSS 3D fallback plus accessible HTML catalog when WebGL is unavailable.
- Browser-local cart; quantity pricing per product: 10–50 at BDT 20; 51–100 at BDT 16.5; 101+ at BDT 16.
- Each box includes one free spoon. Delivery fee is confirmed by the business.
- WhatsApp order composition; no message is sent automatically, and there is no payment processing or server-side order storage.
- The showroom and pack models are illustrative, not a measured reconstruction of a physical store. The owner-supplied honey nuts images are included locally in the catalog, detail dialog and store. They are not used to represent the different Nut Mix product.

## Attribution

Animated navigation links adapted to vanilla HTML/CSS from Skiper UI's free Skiper40 Link000 by @gurvinder-singh02, https://skiper-ui.com/r/skiper40.json (personal/commercial adaptation allowed, attribution retained on the site). Product-card hover treatment is independently implemented, inspired by Aceternity UI's 3D Card Effect, https://ui.aceternity.com/components/3d-card-effect. No paid component source was used.

Three.js is MIT licensed; see `dist/assets/THREE-LICENSE.txt`. Brand name, product details and business contact were supplied by the owner and its public Facebook page.
