<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-upstash
description: "Run Redis commands over REST."
---

# Upstash Connector for Muse

A Muse agent skill that works with an Upstash Redis database over its REST API: read keys, write keys with optional TTL, delete keys, and run batched command pipelines. Writes (set, delete, pipeline) need your confirmation; reads need none. Each database has its own token and host (`.upstash.io`) — declare the database host at connect time. Upstash has a free tier. Draft: written from Upstash's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-upstash
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-upstash
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/upstash

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
