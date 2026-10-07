<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: bluman1-moonraker
description: "Control Klipper printers through Moonraker — job control, temperature, and G-code, with heating and..."
---

# Moonraker 3D Printer Connector for Muse

A Muse agent skill that talks to 3D printers running Klipper through the Moonraker API: print job control (pause, resume, cancel), temperatures, fan speeds, file management, and raw G-code execution. This drives a machine that heats to 200°C+ and moves physically — raw G-code and any heating or motion command are HIGH-risk and always confirmed with the user before running; never let it execute G-code you haven't read. Moonraker usually lives on your local network (the Raspberry Pi next to the printer); API key or trusted-client auth, kept in Muse's secure vault. Draft: written from Moonraker's public API docs, not yet live-tested end-to-end — Skill Harbor never reviews the code, review it yourself before use. No secrets in the repo.

- Listing: https://theskillharbor.com/products/bluman1-moonraker
- Fiche en français: https://theskillharbor.com/fr/products/bluman1-moonraker
- Category: IoT
- Price: Free
- Verification: unverified
- Source repo: https://github.com/bluman1/muse-connectors/tree/main/connectors/moonraker

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
