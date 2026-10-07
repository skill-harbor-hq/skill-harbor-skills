<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-leaf-agriculture
description: "Query farm data from Leaf's provider integrations — fields, operations, and machine data, with sync..."
---

# Leaf Agriculture Connector for Muse

A Muse agent skill that works with Leaf Agriculture's API (withleaf.io), the aggregation layer that normalizes farm data across equipment providers (John Deere, Climate FieldView, CNH, AGCO, and more): fields, operations, machine data, and provider connections. Read-heavy workflows are safe; syncing or pushing data to providers moves real farm records, so the skill confirms the destination and payload with the user before any push. Honest caveat: Leaf's pricing is not published publicly (quote-based, free trial available) — check withleaf.io before committing to production use. Uses Leaf API credentials, kept in Muse's secure vault. Draft: written from Leaf's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-leaf-agriculture
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-leaf-agriculture
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/leaf-agriculture

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
