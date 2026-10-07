<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-ideogram
description: "Generate images with best-in-class text rendering; edit, remix, upscale."
---

# Ideogram Connector for Muse

A Muse agent skill that generates images with Ideogram's v3 API — the strongest option in the catalog for text-in-image rendering (thumbnails and carousels with real, legible words) — plus Magic Fill editing, style remix, upscaling, and image description on the same key. Ideogram is synchronous (no job polling), which makes it the simplest image integration here. Honest note: every generation/edit/remix/upscale spends balance (~$0.05–0.08 per image by model and speed tier), and Ideogram billing auto-tops-up (it refills to $20 when the balance drops below $10, configurable) — read your balance first so top-ups never surprise you; generated image URLs expire, so download immediately. Ideogram has a free plan. Draft: written from Ideogram's published OpenAPI spec, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-ideogram
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-ideogram
- Category: Creativity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/ideogram

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
