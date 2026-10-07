<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-render
description: "List your Render services and recent deploys. Read-only."
---

# Render Connector for Muse

A Muse agent skill with read-only visibility into your Render account: list services (name, type, region) and inspect recent deploys for a service. Read-only by design — no deploy, suspend, restart, or env-var commands ship. Honest note: a Render API key can see every workspace the account belongs to — the key's reach is the account's reach. Render has a free tier. Draft: written from Render's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-render
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-render
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/render

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
