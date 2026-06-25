# RUN 2026-06-25 — GBP booking CTA library

## What shipped
- Added `google-business-profile-booking-cta-templates.html`, a new public helper page targeting Google Business Profile booking-link, request-quote, consultation, and appointment-CTA intent for local operators.
- Wired the new page into the core Google Maps Visibility Sprint cluster so it compounds with the existing review, post, description, services, category, Q&A, attributes, and photo helper pages.

## Why this lane
- Native marketplaces remain slower and less reliable than the existing GitHub Pages + Stripe storefront.
- Booking / estimate CTA wording is a tight adjacent search-and-conversion job that naturally upsells into the same $99 audit and $349 DFY optimization.
- The current stack already references appointment qualifiers and consultations, so a standalone booking CTA helper page is a fast compounding extension instead of a new funnel.

## Integration targets
- `index.html`
- `distribution-kit.html`
- `google-maps-audit-directory.html`
- `google-business-profile-attributes-templates.html`
- `google-business-profile-photo-prompts.html`
- `launch-kit.html`
- `README.md`
- `google-maps-visibility-marketplace-launch-kit.zip`

## Verification target
- Keep both existing Stripe checkouts live.
- Push the helper page and linked cluster updates to GitHub Pages.
- Re-check raw GitHub and Pages URLs after deploy lag clears.
