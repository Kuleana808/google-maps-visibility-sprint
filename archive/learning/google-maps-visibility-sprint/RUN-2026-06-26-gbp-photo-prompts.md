# RUN 2026-06-26 — GBP photo prompt library

## What shipped
- Added `google-business-profile-photo-prompts.html`, a new public helper page targeting Google Business Profile photo-idea / photo-example / before-and-after-image intent for local operators.
- Wired the new page into the core Google Maps Visibility Sprint cluster so it compounds with the existing review, post, description, services, category, Q&A, and attributes helper pages.

## Why this lane
- Native marketplaces remain slower and less reliable than the existing GitHub Pages + Stripe storefront.
- GBP photo/upload intent is a tight adjacent search job that naturally upsells into the same $99 audit and $349 DFY optimization.
- The current stack already references photos as part of the paid offer, so a standalone photo helper page is a fast compounding extension instead of a new funnel.

## Integration targets
- `index.html`
- `distribution-kit.html`
- `google-maps-audit-directory.html`
- `google-business-profile-post-prompts.html`
- `google-business-profile-attributes-templates.html`
- `launch-kit.html`
- `README.md`
- `google-maps-visibility-marketplace-launch-kit.zip`

## Verification target
- Keep both existing Stripe checkouts live.
- Push the helper page and linked cluster updates to GitHub Pages.
- Re-check raw GitHub and Pages URLs after deploy lag clears.
