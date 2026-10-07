<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-podbean
description: "Manage your Podbean podcast from Muse — episodes, publishing, and a permanent free plan to start on."
---

# Podbean Podcast Connector for Muse

A Muse agent skill that manages a Podbean podcast through Podbean's API: list and create episodes, publish and schedule them, and manage podcast metadata. Publishing is public and hard to take back — the skill confirms with the user before any publish or schedule. Honest note from its own SKILL.md: analytics are not implemented (Podbean's analytics API isn't covered), so check stats in the Podbean dashboard instead. Podbean offers a permanent free plan (limited storage) with paid tiers for unlimited hosting. Uses a Podbean API key, kept in Muse's secure vault. Draft: written from Podbean's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-podbean
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-podbean
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/podbean

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
