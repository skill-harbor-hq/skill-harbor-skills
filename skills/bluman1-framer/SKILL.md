<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-framer
description: "Verify a Framer project's Server API connection."
---

# Framer Connector for Muse

A Muse agent skill that verifies a Framer project's Server API connection: Framer's Server API is WebSocket/SDK-only (no REST surface), so the connector performs the official handshake from the `framer-api` npm package as a connection check — a successful check proves the API key and project pair work. Honest note: deeper operations (pages, CMS, deploys) run through the official npm package, not this CLI, and are intentionally out of scope; the key is bound to one project only. Framer has a free plan. Draft: the handshake transport is pinned from the official package source; the client has not been run against Framer's servers yet — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-framer
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-framer
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/framer

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
