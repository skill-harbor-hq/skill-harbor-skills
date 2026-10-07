<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-home-assistant
description: "Read entity states and call services on your Home Assistant instance. Service calls are confirmed..."
---

# Home Assistant Connector for Muse

A Muse agent skill that talks to your own Home Assistant instance: list entity states (optionally filtered by domain), read one entity, and call services (e.g. `light.turn_on`). Service calls act on the physical home (lights, locks, climate) — confirm the exact domain, service, entity, and parameters first, unless standing permission exists; reading needs no confirmation. Uses a Home Assistant long-lived access token (your profile > Security > Long-Lived Access Tokens), kept in Muse's secure vault. Note: the instance URL is passed with every command — treat it as secret-adjacent and never post it publicly. Home Assistant is free and self-hosted. Draft: written from Home Assistant's public REST API docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-home-assistant
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-home-assistant
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/home-assistant

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
