<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-ecovacs
description: "Drive your DEEBOT robot vacuum from Muse — status, cleaning jobs, and maps, with physical commands..."
---

# Ecovacs DEEBOT Connector for Muse

A Muse agent skill that talks to Ecovacs DEEBOT robot vacuums through the Ecovacs API: device status, cleaning sessions, maps, and remote commands (start, stop, return to dock, spot cleaning). This one moves a physical object around your home — always confirm with the user before starting, stopping, or redirecting a cleaning job, especially with pets or people around. Honest caveat from its own SKILL.md: some endpoints are not confirmed against Ecovacs's public docs and pricing/quotas are not published, so expect trial and error and start read-only to validate your credentials. Uses Ecovacs account credentials, kept in Muse's secure vault. Draft: written from Ecovacs's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-ecovacs
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-ecovacs
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/ecovacs

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
