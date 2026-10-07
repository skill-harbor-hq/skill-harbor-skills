<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-remove-bg
description: "Remove the background from an image with the remove.bg API: submit a local file or an image URL..."
---

# remove.bg Connector for Muse

💳 Paid API required: this connector needs a paid third-party API — the listing is free, but usage is billed. See Prerequisites for costs.

A Muse agent skill that removes image backgrounds with the remove.bg API: submit a local file or an image URL, get back a transparent PNG saved to a local path; also checks the account's remaining credits. Every `process` call burns paid credit (roughly $0.11 to $0.23 per full-size image, less for previews) — confirm before processing, or work inside an explicit budget; run `account` first to see the balance. Free signup includes 1 credit only. Note: images are processed on remove.bg's servers — do not send sensitive or private imagery without the user's okay. No video support. Uses a remove.bg API key, kept in Muse's secure vault. Draft: written from remove.bg's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-remove-bg
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-remove-bg
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/remove-bg

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
