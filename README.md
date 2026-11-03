# BREW CO. — Digital QR Menu (responsive, multi-page)

## Open
Extract the ZIP and open `index.html` in any browser. No server or JavaScript needed.
Fonts (Poppins, Montserrat) load from Google Fonts; without internet the page falls back to system fonts.

## Pages
- `index.html` — home: hero, then featured items for Coffee, Non-coffee, Starters, Mains and Pastries, each with "View all".
- `coffee.html`, `non-coffee.html`, `starters.html`, `mains.html`, `pastries.html` — the "View all" pages with every item in that category.

The navbar (logo, menu button, cart) and the "We deliver to you!" footer are the same on every page;
only the page content changes. The ☰ menu icon is decorative (no dropdown).

## Responsive
- Small phones (under 360px): compact sizes.
- Phones: single-column list, exactly like the design.
- Tablets (600px+): two columns of items.
- Laptops and desktops (1024px+): three columns, large hero.
- Large screens (1440px+): wider layout.

## QR code
`qr.html` shows the printable QR code (`assets/qr.png`). It opens https://hasanjamil2861-stack.github.io/Digital-Menu/ — if the site link changes, generate a new QR.

## Changing photos, names and prices
Starters and Mains prices are placeholders — update them to the real prices.
Each featured item appears in `index.html` and in its category page, so change both.
To swap a photo, replace the file in `assets/` keeping the same file name.
The banner image is `assets/hero-latte.jpg`.
