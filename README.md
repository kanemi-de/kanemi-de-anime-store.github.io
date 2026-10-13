# ⛩️ KANEMI-DE — Anime Figures & Collectibles

**Your universe of anime collectibles.**

A premium, English-language, mobile-responsive showcase for collectible anime figures. No server, npm packages, CDN, fonts, API keys or online assets are needed to open the site.

## Getting started

1. Extract the ZIP.
2. Open `index.html` in a desktop or mobile browser.
3. Explore **53 distinct verified product listings** across 9 anime franchises.
4. Search by character or series, filter products, sort by price, save favorites, view figure details, and add to the **demonstration-only shopping bag**.

The logo and every display illustration are stored in this ZIP. **No website element loads images from external links.**

## Store sections

- Naruto / Naruto Shippuden
- One Piece
- Dragon Ball
- Demon Slayer
- Jujutsu Kaisen
- Attack on Titan
- Chainsaw Man
- My Hero Academia
- Bleach

## Product prices and provenance

The prices shown are **actual published price references** sourced from figure listings (primarily Crunchyroll Store) and recorded on October 12, 2026. Every product's provenance is documented in:

`data/PRECIOS-Y-FUENTES.csv` and `data/productos.json`

The browser does not contact these external source URLs. Prices are snapshots, not independently confirmed live prices, and may change due to promotions, availability, taxes, or retailer policies. They are **not offered sale prices by KANEMI-DE** until verified by its operator.

## Product photography — important

**The supplied product visuals are original, stylized SVG illustrations, not photos of genuine physical figures.** They are intentionally marked `ILLUSTRATION · PHOTO PENDING` and must not be represented as photos of official products.

The images from external retailers could not be downloaded in this session, and commercial reuse rights were not verified. To replace illustrative artwork with real product photographs that your store is authorized to use:

1. Save photos for the correct product into `assets/photos/`, preferably as compressed `.webp` files.
2. Open `assets/js/catalog.js` and replace that product's `image` path (e.g. `assets/products/km-001.svg`) with `assets/photos/km-001.webp`.
3. Verify that photos represent that exact listed edition/variant and that your business has the required rights to use them.
4. Remove the demonstration image disclaimers once each photo has been replaced and verified.

**No hotlinking or external images are required.**

## Advisor number

The current number is **+1 (202) 555-0148**, a deliberately fictional US example reserved for illustrative use. It is not an active business contact or owned by KANEMI-DE.

To launch, change both the number and the `DEMO CONTACT — NOT ACTIVE` badge in `index.html` to your verified business phone. Do not publish the placeholder as a real support line.

## Demo versus production

**Works locally:** responsive storefront, 53 product listings, image art, category navigation, search, filters, sorting, product detail dialog, wishlist, shopping bag, quantity adjustment, stored cart state.

**Not activated:** real stock control, checkout, order collection, credit-card processing, shipping, verified business address, real customer-service line.

Before launch: replace the artwork with licensed product photos; verify prices and inventory with suppliers; set up tax, shipping and privacy policies; connect a real ecommerce/backend platform and payment processing; use your verified contact details.

## Files

```
KANEMI-DE/
├─ index.html                 # Main responsive storefront
├─ README.md                  # Setup & commercial transparency
├─ assets/
│  ├─ logo.webp               # Embedded custom original brand logo
│  ├─ favicon.png
│  ├─ css/style.css            # Complete responsive theme
│  ├─ js/catalog.js            # Local self-contained catalog
│  ├─ js/app.js                # Search, favorites, demo cart
│  ├─ products/km-*.svg        # 53 distinct original preview artworks
│  └─ photos/                 # Place authorized product photos here
├─ data/
│  ├─ productos.json           # Catalog + source references
│  └─ PRECIOS-Y-FUENTES.csv    # Price provenance and reference date
└─ docs/
   └─ LAUNCH-CHECKLIST.md
```

## Intellectual property

KANEMI-DE is an independent anime collectibles prototype. Names of anime series, characters, manufacturers, and related trademarks belong to their respective owners. No official affiliation is claimed. Product photos must be used with permission where required.

© 2026 KANEMI-DE. Original site theme and editorial text prepared for this project.
