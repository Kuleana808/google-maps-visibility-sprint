# RUN-2026-06-27 — tree service marketplace pack

## What shipped
- Added `tree-service-marketplace-pack.html` as a dedicated marketplace/listing surface for tree service operators.
- Wired the new pack into `tree-service-google-maps-audit.html`, `index.html`, `distribution-kit.html`, `vertical-quickstart.html`, `launch-kit.html`, `google-maps-audit-directory.html`, `marketplace-assets.html`, and `README.md`.
- Rebuilt `google-maps-visibility-marketplace-launch-kit.zip` so the new pack is included in the handoff bundle.

## Why this matters
- The cluster already had a tree-service proof page and live Stripe checkouts.
- The missing gap was listing-ready packaging for storm cleanup, removals, stump grinding, and emergency-call seller workflows.
- This turns an existing proof asset into a tighter marketplace lane without depending on blocked marketplace automation.

## Verification target
- New file present locally: `tree-service-marketplace-pack.html`
- Cross-links present on the tree-service proof page and main discovery surfaces
- ZIP rebuilt with the new pack included exactly once
