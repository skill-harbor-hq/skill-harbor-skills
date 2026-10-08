<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-network-bgp-diagnostics
description: "Read-only BGP troubleshooting with Muse: neighbor states, route exchange, prefix policy, AS path..."
---

# Network BGP Diagnostics

Curated by Skill Harbor: a diagnostics-only BGP troubleshooting guide that makes Muse triage a broken or flapping BGP session with read-only evidence collection, never with guesses or disruptive resets. It opens with a read-only triage flow (identify the neighbor, address family, VRF and ASNs, capture summary state and last reset reason, prove reachability to the peer, check route policy references before assuming transport failure), then gives a state interpretation table covering Idle through Established with the first checks for each state. Transport checks cover ping, traceroute and TCP port 179 reachability without disabling ACLs as a diagnostic shortcut. Route policy checks cover advertised versus received routes, prefix-lists and route-maps, and AS path review with careful regex token boundaries. A Python parser pattern turns show bgp summary output into structured data, and a strict change-window-only section lists what must never be suggested as automatic diagnostics: clearing sessions, changing authentication or timers, enabling extra received-route storage, or relaxing firewall policy. Community-contributed to the affaan-m/ECC repository (MIT). Honest caveats: this is triage, not a fix, and real fixes belong in a reviewed change window; you need actual network gear and CLI access for it to be useful; it will not replace a network engineer. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-network-bgp-diagnostics
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-network-bgp-diagnostics
- Category: Network
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/network-bgp-diagnostics/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
