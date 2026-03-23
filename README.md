# Link Bus Uganda

Single-page web app for Link Bus Uganda booking, routes, schedules, terminals, courier rates, and passenger help content.

## Current System

This repository currently contains a static frontend implemented in one file:
- index.html

Tech used in the current implementation:
- React 18 (CDN + Babel in-browser JSX)
- Tailwind CSS (CDN)
- GSAP + ScrollTrigger (CDN)
- Plain HTML deployment (no build step)

## Features Implemented

- Sticky responsive navigation with mobile menu
- Hero + booking widget (origin, destination, travel date)
- Route cards with quick select behavior
- Live schedule table with status pills
- Fleet section with animated SVG bus
- Services and courier rates sections
- Safety/trust section and reviews
- Terminals grid and FAQ accordion
- Footer contact details and WhatsApp CTA
- GSAP animations:
  - Hero entrance timeline
  - Staggered route reveal
  - Section scroll reveals
  - Floating fleet bus animation
  - Pulsing WhatsApp button glow

## Run Locally

Option 1: Open directly
- Open index.html in a browser.

Option 2: Use a local static server (recommended)
- Python 3:
  - python3 -m http.server 4173
- Then open:
  - http://localhost:4173

## Activate Mobile Money Checkout

MTN and Airtel payment buttons are wired in the booking widget.

To activate live checkout, set your Flutterwave public key before the app script in index.html:

<script>
  window.FLW_PUBLIC_KEY = "FLWPUBK_TEST-xxxxxxxxxxxxxxxxxxxxx-X";
</script>

Notes:
- Without this key, the app runs in safe demo mode and shows manual MTN/Airtel instructions.
- Use your production key only on trusted deployments and always verify payment server-side in a backend before issuing final tickets.

## Notes

- Internal anchor links have been validated against existing section IDs.
- No build pipeline is required for the current version.
- If you want production optimization, the next step is to migrate to a bundled React setup (Vite/Next.js).
