# RUN — 2026-06-27 HVAC marketplace pack

## Goal
Add a broad HVAC marketplace-style listing asset so the live Google Maps Visibility Sprint can be sold faster on marketplace, classified, service-marketplace, and DM-first surfaces without relying only on the narrower no-cool HVAC angle.

## What changed
- Added `hvac-marketplace-pack.html` with:
  - HVAC-specific listing title bank
  - package framing for the existing $99 audit and $349 DFY offer
  - broad repair / install / tune-up / emergency-service hook bank
  - buyer requirements and fast-close reply snippets
  - links to the existing live Stripe checkout paths
- Wired the new pack from `distribution-kit.html`, `launch-kit.html`, `index.html`, `hvac-google-maps-audit.html`, and `README.md`.
- Rebuilt `google-maps-visibility-marketplace-launch-kit.zip` so the new HVAC pack and this run note ship inside the downloadable bundle.

## Why this lane
General HVAC reaches a wider listing market than the peak-heat-only no-cool page: AC repair, furnace repair, heat pumps, installs, maintenance, and emergency service all fit the same productized offer and can be sold on public listing surfaces immediately.

## Live assets
- Main offer page: https://kuleana808.github.io/google-maps-visibility-sprint/
- HVAC page: https://kuleana808.github.io/google-maps-visibility-sprint/hvac-google-maps-audit.html
- New pack target URL after push: https://kuleana808.github.io/google-maps-visibility-sprint/hvac-marketplace-pack.html
- $99 audit checkout: https://buy.stripe.com/14A3cwaYr7mD4l2bFSenS01
- $349 DFY checkout: https://buy.stripe.com/7sY7sM1nR0Yf8Bi11eenS02

## Verification
- Confirmed local wiring references in the distribution kit, launch kit, main index, HVAC proof page, and README inventory.
- Rebuilt the launch ZIP and verified it contains both `hvac-marketplace-pack.html` and `RUN-2026-06-27-hvac-marketplace-pack.md`.

## Next move
Push the updated local-seo sprint stack so the new HVAC marketplace pack is publicly reachable, then reuse it as the copy source for HVAC marketplace listings, directory submissions, partner/resource pages, and community posts that can route buyers into the existing live Stripe checkout flow.
