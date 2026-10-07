<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-monday
description: "List boards, read items, create items. Project management over GraphQL."
---

# monday.com Connector for Muse

A Muse agent skill that works your monday.com boards through one GraphQL endpoint: list boards, read items on a board, and create items. Creating an item is a write — the skill confirms the values first; reading needs no confirmation. Uses a personal monday.com API token, kept in Muse's secure vault. Honest note: GraphQL calls consume a per-minute complexity budget — the skill's queries stay simple and pages accordingly. Draft: written from monday.com's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-monday
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-monday
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/monday

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
