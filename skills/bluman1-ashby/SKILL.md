<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-ashby
description: "Search public jobs without a key and manage your Ashby recruiting pipeline — candidate moves are..."
---

# Ashby ATS Connector for Muse

A Muse agent skill that works with Ashby's recruiting platform on two levels: public job search needs no credentials at all, while the authenticated API manages jobs, candidates, and interviews. Write actions that move candidates through a real hiring pipeline (stage changes, interview scheduling) are always confirmed with the user before they run — a mis-sent candidate email or an accidental stage move is hard to undo. Public job boards stay free; full ATS access requires an Ashby account. Uses Ashby API credentials for the authenticated part, kept in Muse's secure vault. Draft: written from Ashby's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-ashby
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-ashby
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/ashby

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
