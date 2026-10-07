<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-unsplash
description: "Search, browse, and download free stock photos — photographers always credited."
---

# Unsplash Connector for Muse

A Muse agent skill for Unsplash's free stock photo library: search photos, browse the latest, look up a photo's details, browse a photographer's portfolio or a topic, and download images. Downloads honor Unsplash's guidelines — the download endpoint is hit first so the photographer gets credited, and images are downloaded and self-hosted rather than hotlinked, with the photographer credit shown. Read-only at the Client-ID tier. Uses a free Unsplash access key (unsplash.com/developers), kept in Muse's secure vault. Rate limits: ~50 requests/hour for demo apps, 5,000/hour for approved production apps. Draft: written from Unsplash's public API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-unsplash
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-unsplash
- Category: Fun & games
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/unsplash

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
