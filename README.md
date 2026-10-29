# MahakumbhStays

Responsive frontend prototype for an accommodation marketplace focused on Nashik and Trimbakeshwar.

## Run locally

Install Node.js, then run from this directory:

```sh
npm run dev
```

Open http://localhost:3000. No dependency installation is required.

## Included

- Homepage, destination collections, FAQs and travel guide
- Ten demo properties with search, filters, sorting and saved stays
- Property details, room selection and photo categories
- Guest checkout, simulated payments, confirmation and demo voucher
- Customer, property partner and admin demo views
- Property listing introduction and browser-local listing drafts
- Responsive layouts and mobile booking bar

## Project structure

- `dist/` — frontend HTML, CSS, JavaScript and local image assets
- `server.cjs` — lightweight local preview server

The frontend uses plain JavaScript and CSS. No backend, database, real authentication, payment gateway or messaging service is connected. Saved stays and listing drafts use browser storage. All properties, rates, ratings, availability and bookings are illustrative.

## Validation

```sh
npm run check
node --check dist/premium.js
```

## Images

Local Indian-style accommodation images are AI-generated illustrations of fictional properties. Destination photographs are historical images from Wikimedia Commons; photographer and license credits are displayed in the site footer. They do not depict the 2027 event.
