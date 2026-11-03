# BREW CO. — Digital QR Menu

A responsive, multi-page QR digital menu built with **HTML & CSS** only.
Customers scan the QR code on the table to open the menu on their phones.

## Live links
- **Menu:** https://hasanjamil2861-stack.github.io/Digital-Menu/
- **QR code page:** https://hasanjamil2861-stack.github.io/Digital-Menu/qr.html

## Pages
- `index.html` — home: hero banner, then featured items for Coffee, Non-Coffee, Starters, Mains and Pastries, each with "View all".
- `coffee.html`, `non-coffee.html`, `starters.html`, `mains.html`, `pastries.html` — the "View all" pages with every item in that category.
- `qr.html` — printable QR code that opens the menu.

The navbar (logo, menu icon, cart) and the "We deliver to you!" footer are the same on every page.
The ☰ menu icon and the cart icon are decorative only and not clickable, as required.

## Responsive
- Small phones (under 360px): compact sizes.
- Phones: single-column list, matching the provided design.
- Tablets (600px+): two columns of items.
- Laptops and desktops (1024px+): three columns and a larger hero.
- Large screens (1440px+): wider layout.

## QR code
`qr.html` shows the QR code (`assets/qr.png`), which opens https://hasanjamil2861-stack.github.io/Digital-Menu/.
Press **Ctrl + P** on that page to print only the QR card for the tables.
If the site link changes, a new QR code must be generated.

## Editing the menu
- Each featured item appears in `index.html` and in its category page, so update both.
- To change a photo, replace the file in `assets/` and keep the same file name.
- The hero banner image is `assets/hero-latte.jpg`.

## Tech stack
HTML5 · CSS3 · Google Fonts (Poppins, Montserrat) · GitHub Pages