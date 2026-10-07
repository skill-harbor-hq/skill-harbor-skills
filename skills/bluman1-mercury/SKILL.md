<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-mercury
description: "View Mercury bank accounts and transactions. Read-only by design."
---

# Mercury Connector for Muse

A Muse agent skill with read-only access to your Mercury banking: list bank accounts and view recent transactions per account. This connector cannot move money or change anything — there are no write commands at all. Honest note: use a Read-Only API token (generated at app.mercury.com > Settings > API Tokens; no IP whitelist needed for read-only); Mercury banking itself is free for eligible US companies. Draft: written from Mercury's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-mercury
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-mercury
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/mercury

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
