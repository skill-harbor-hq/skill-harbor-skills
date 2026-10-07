<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-restream
description: "Manage Restream multistreaming: read your profile, list streaming destinations (channels), toggle..."
---

# Restream Connector for Muse

A Muse agent skill that manages Restream multistreaming without opening the dashboard: read your profile, list streaming destinations (channels), toggle destinations or edit channel metadata, and retrieve your stream key. Confirm before toggling or editing (it changes what is live) and before anything that changes the stream key — rotating it disconnects every active encoder using the old key; treat the key output as a live secret and never paste it into chat, logs, or tickets. Live chat is WebSocket-only and out of scope. OAuth 2.0, token kept in Muse's secure vault. Restream has a free plan. Draft: written from Restream's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-restream
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-restream
- Category: Streaming
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/restream

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
