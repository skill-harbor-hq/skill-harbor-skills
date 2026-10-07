<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-transistor
description: "Manage podcast hosting on Transistor.fm: list shows and episodes, create draft episodes, update or..."
---

# Transistor.fm Connector for Muse

💳 Paid API required: this connector needs a paid third-party API — the listing is free, but usage is billed. See Prerequisites for costs.

A Muse agent skill that manages podcast hosting on Transistor.fm: list shows and episodes, create draft episodes, update or delete them, and upload episode audio via Transistor's two-step upload flow. `episode-create` makes a draft by default — never publishes without a separate explicit confirmation. Confirm before creating, updating, deleting, or uploading (upload consumes storage on your Transistor plan). The API key is account-scoped: you can only touch your own shows. Transistor.fm is paid hosting only — no free tier. Uses a Transistor API key, kept in Muse's secure vault. Draft: written from Transistor's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-transistor
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-transistor
- Category: Podcast
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/transistor

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
