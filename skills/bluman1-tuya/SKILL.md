<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-tuya
description: "Control Tuya smart devices from Muse — lights, plugs, and locks, with home actions always confirmed."
---

# Tuya IoT Connector for Muse

A Muse agent skill that controls Tuya-platform smart devices through the Tuya Cloud API: device status, on/off commands, brightness and color, locks, and scenes — covering the huge ecosystem of white-label Tuya devices (bulbs, plugs, switches, sensors). Honest cost note: Tuya's IoT Core cloud service runs on a free trial (around 26,000 API calls/month, no overage billing — the service pauses when the allowance runs out) that you start from the Tuya IoT Platform console; paid editions are enterprise-priced, so this connector is practical mainly within the trial allowance. It acts on your physical home — always confirm before any write that changes the home's state. Uses your Tuya IoT Platform credentials, kept in Muse's secure vault. Draft: written from Tuya's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-tuya
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-tuya
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/tuya

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
