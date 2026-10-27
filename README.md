# Price Marine Construction website

Redesign of https://www.pricemarineconstruction.com for Price Marine Construction, Tarpon Springs, FL.

- Live site (GitHub Pages): https://danielmely.github.io/price-marine-construction/
- Single self-contained file: `index.html` (no build step, no server)
- Works on phone and desktop, light and dark mode

## How updates work

Every edit is committed and pushed to `main`. GitHub Pages republishes about a minute after each push. This README's change log is updated with every push.

## Page sections

Header with logo, nav and Call button; Hero with photo; Services; Roof structures; Maintenance; Gallery; About us (stats and partner brands); Contact with quote form; Footer.

## Change log

Newest first.

### 2026-10-26
- Footer social buttons are now icon-only (Facebook, Instagram, Google logos). Contact section buttons keep their names.
- Removed the review count from the Google rating; it now shows just 4.7 stars everywhere.
- Linked the 4.7 star Google rating to the Google listing and added a "Google reviews" button next to the social buttons (Contact and footer).
- Added Facebook and Instagram buttons in Contact and the footer.
- Added the verified Google rating (4.7) and "Licensed & insured" in the hero, About us stats, Contact and footer.
- Published the site to GitHub (`danielmely/price-marine-construction`) for GitHub Pages hosting; added this README.
- Created a standalone test file for opening the site outside Claude (Safari).

### Content changes
- Changed the roof wind rating from "145 MPH" to "140+ MPH" everywhere.
- Kept "Everlast Seawalls" as a text tile with a black outline; other brand logos use a light grey outline.
- Brand logos now have transparent backgrounds with a slightly thick outline so they read on any background.
- Gallery tape-measure ruler switched from yellow to light grey.

### Layout and wording fixes
- Removed the light blue "Roof structures" eyebrow text in the roof section.
- Renamed "About" to "About us" (nav and section).
- Kept the Maintenance subheadings aligned in a fixed-width label column.
- Centered the logo in About us and the "Brands we build with" heading on mobile and desktop.
- Fixed horizontal overflow at 1024 to 1100 px and at 320 px widths.

### Branding and imagery
- Added the Price Marine Construction logo to the top left of the header, the menu, About us and the footer.
- Used the boat house photo as the first image on the home screen.
- Added partner logos under "Brands we build with" (IMM Quality Boat Lifts, DECO Boat Lifts, ESP, Marina Products & Equipment, GatorDock, Decks & Docks Lumber Co., Truline, Everlast Seawalls).
- Gallery tiles carry a continuous tape-measure ruler with inch numbering.

### Design
- Switched to a coastal color palette using the brighter blues from the original site.
- Made the layout fully responsive for mobile and desktop.

### Initial redesign
- Rebuilt the original Wix site as a cleaner, easier to navigate one-page site: sticky header with nav, hero with calls to action, six services, roof structures, maintenance packages, gallery, About us, brands, contact details and quote form.
- Quote form builds the request text and copies it, since a static page has no server to send email.
- Call button uses a phone link (727.409.4572).

## Not included yet

- Real project photos in the gallery (tiles still link to the old gallery pages).
- Drone video embeds.
- Customer review quotes.
- License number next to "Licensed & insured".
- Automatic email delivery for the quote form.
