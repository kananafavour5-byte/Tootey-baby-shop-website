# Tootey Baby Shop — local preview

Open index.html in a browser to review the shop without hosting. Keep the assets folder, app.js, catalogue.js and style.css together.

Includes 35 sample listings copied from the newborn shopping checklist, nine categories, three sample packages, product details, search, and an in-memory enquiry bag. The bag resets on page reload. No customer account, payment or order database is connected.

Confirmed WhatsApp number: 0798577025 (international link: 254798577025). Enquiry links prepare a message; they do not send it automatically.

All prices and product illustrations are placeholders. Real photos, specifications, availability, package contents and delivery areas/charges require owner confirmation before launch. This site has not been published; domain and mobile app were not modified.

Assets: logo.png, clouds.png and connection.jpg were copied from the existing Tootey app, whose ASSET-PROVENANCE.md records them as generated brand imagery. Product illustrations are original inline SVG placeholders. No third-party product photos were downloaded.

Checked 26 October 2026: JavaScript syntax; narrow mobile browser layout; product details; category filtering; search; package contents; adding products/packages; quantity recalculation; removal and empty bag; prepared WhatsApp URL and contents. No WhatsApp message was sent. Desktop visual QA remains to be completed.

## GitHub and Vercel deployment

Use a separate repository named tootey-baby-shop. Upload the contents of this folder as the repository root. Do not include the mobile app or any account/profile data.

Vercel import settings: Framework Preset Other; Root Directory repository root; no build command; Output Directory repository root. This is a static site with no dependency installation or environment variables required. Keep the generated Vercel address initially; no domain/DNS changes are needed.

Preview search indexing is disabled through robots.txt and X-Robots-Tag. Remove these restrictions only when the real catalogue is ready for public launch. Placeholder labels remain visible.
