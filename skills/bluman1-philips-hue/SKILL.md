<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-philips-hue
description: "Control Philips Hue lights locally: list lights and rooms, set brightness/color, activate scenes..."
---

# Philips Hue Connector for Muse

A Muse agent skill that controls your Philips Hue setup over the local Hue CLIP v2 API: list lights and rooms, set light state (on/off, brightness, color), set room-level grouped lights, activate scenes, and read motion, temperature, and light-level sensors. Every write acts on the physical home — confirm the exact light/room and the change first (whole-home changes need explicit confirmation); reading needs none. Pair once with the bridge's physical link button — no cloud key needed; the local API works on the same LAN, or remotely via the Hue Remote API (OAuth). Free — requires a Hue Bridge. Draft: written from Philips Hue's public CLIP v2 docs, not yet live-tested end-to-end — this listing's unverified status reflects that. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-philips-hue
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-philips-hue
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/philips-hue

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
