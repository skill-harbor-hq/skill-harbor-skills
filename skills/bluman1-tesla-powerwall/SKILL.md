<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-tesla-powerwall
description: "Monitor your Powerwall and solar from Muse — battery, grid, and backup reserve, reads first."
---

# Tesla Powerwall Energy Connector for Muse

A Muse agent skill that talks to Tesla's Fleet API energy endpoints for Powerwall and solar sites: battery charge, solar production, grid import/export, backup reserve, and site status. It's primarily a monitoring tool — reads are safe anytime — with a small set of energy-setting writes that are always confirmed with the user before changing how your home stores or exports power. Tesla historically offered a free developer tier (around 200 requests/hour/site); check Tesla's current developer terms before heavy use. Uses Tesla Fleet API credentials, kept in Muse's secure vault. Draft: written from Tesla's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-tesla-powerwall
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-tesla-powerwall
- Category: Energy
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/tesla-powerwall

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
