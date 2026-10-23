<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gadget-shelly-plugs
description: "Switch Shelly Gen 4 plugs and read supported power or energy measurements through Muse Home Link..."
---

# Shelly Plugs

Switch Shelly Gen 4 plugs and read supported power or energy measurements through Muse Home Link, using the local Shelly RPC API after confirming the actual plug and its attached load. It matches _http._tcp model/hostname metadata and Shelly.GetDeviceInfo (model, app, gen, firmware, auth_en), reads Switch.GetStatus before acting, and uses digest authentication with approved stored credentials when auth_en is true — the password is never placed in a command. It is not the Gen 1 protocol.

- Listing: https://theskillharbor.com/products/gadget-shelly-plugs
- Fiche en français: https://theskillharbor.com/fr/products/gadget-shelly-plugs
- Category: Smart Home
- Price: Free
- Verification: unverified
- Source repo: https://github.com/facebookincubator/muse-gadget-sdk/blob/main/skills/gadget-shelly-plugs/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
