# RUN-2026-06-27 — junk removal marketplace pack

## What shipped
- Added `junk-removal-marketplace-pack.html` as a dedicated marketplace/listing surface for junk removal operators.
- Wired the new pack into `junk-removal-google-maps-audit.html`, `distribution-kit.html`, `vertical-quickstart.html`, `launch-kit.html`, `google-maps-audit-directory.html`, and `README.md`.
- Rebuilt `google-maps-visibility-marketplace-launch-kit.zip` so the new pack is included in the handoff bundle.

## Why this matters
- The cluster already had a junk-removal proof page and live Stripe checkouts.
- The missing gap was listing-ready packaging for same-day pickup, furniture haul-away, appliance removal, estate cleanouts, and bulky-item seller workflows.
- This turns an existing proof asset into a tighter marketplace lane without depending on blocked marketplace automation.

## Verification target
- New file present locally: `junk-removal-marketplace-pack.html`
- Cross-links present on the junk-removal proof page and main discovery surfaces
- ZIP rebuilt with the new pack included exactly once
