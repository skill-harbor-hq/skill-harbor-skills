<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-unifi-protect
description: "Check your UniFi Protect cameras from Muse — snapshots, recordings, and settings, all local..."
---

# UniFi Protect Camera Connector for Muse

A Muse agent skill that works with a UniFi Protect NVR on your local network: camera lists and live states, snapshots, recording queries, and camera settings. Everything stays local — no cloud account, no footage ever leaves your network through this connector. Honest caveats from its own SKILL.md: several write paths are documented but not tested against a live console (start read-only and validate), and self-signed certificates are expected on local UniFi consoles — that's normal, not a red flag. Snapshots and recordings contain real footage of your home: never share them without the user's explicit agreement, and confirm before any setting change. Uses your UniFi console credentials, kept in Muse's secure vault. Draft: written from UniFi's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-unifi-protect
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-unifi-protect
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/unifi-protect

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
