<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-network-interface-health
description: "Interface diagnostics with Muse for routers, switches, and Linux hosts: CRCs, drops, duplex..."
---

# Network Interface Health

Curated by Skill Harbor: network interface diagnostics that make Muse reason about link health like a network engineer. The core principle is that trends matter more than absolute numbers: capture a baseline, wait a measurement interval, capture again, then compare increments. It ships a counter reference table (CRC means bad cable, dirty fiber, bad optic or duplex mismatch; runts point to duplex mismatch; giants to MTU mismatch; input drops to bursts or queue pressure; output drops to congestion) and a diagnosis flow for the three classic cases: CRCs or input errors (confirm they are incrementing, check both ends of the link, replace the cable before touching routing), drops (separate input from output drops, compare rate against capacity, prove congestion before tuning queues), and duplex/speed (prefer auto-negotiation on modern links, never mix fixed on one side with auto on the other). Includes a safe Python parser for show interfaces output that slices per-interface blocks from header to header instead of using arbitrary character windows, worked examples (CRCs on one switch port, WAN slow but LAN fine), and anti-patterns (clearing counters before saving a baseline, looking at only one side of a link). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: read-only diagnosis, you still need device access and change windows for fixes; it does not replace monitoring or a network engineer for production incidents....

- Listing: https://theskillharbor.com/products/affaan-m-ecc-network-interface-health
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-network-interface-health
- Category: Networking
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/network-interface-health/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
