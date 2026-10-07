<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-aqara
description: "Control Aqara smart home devices (locks, scenes, sensors) via the Aqara Cloud API — an honest draft..."
---

# Aqara Smart Home Connector for Muse

A Muse agent skill that reads Aqara device status and sends commands through the Aqara Cloud API (device lists, scenes, and device actions). Honest caveat from its own SKILL.md: some API paths and signatures are NOT confirmed against Aqara's public docs, so expect trial and error — and always confirm with the user before any lock, scene, or automation change that physically affects the home. Aqara authentication is fiddly (a developer app with an OAuth code flow); start in read-only mode to validate credentials before touching anything that moves or locks. Uses Aqara API credentials, kept in Muse's secure vault. Draft: written from Aqara's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-aqara
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-aqara
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/aqara

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
