<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-homelab-pihole-dns
description: "Pi-hole for your home network: network-wide ad and tracker blocking via DNS, with Docker install..."
---

# Homelab Pi-hole DNS

Curated by Skill Harbor: a Pi-hole skill that turns a Raspberry Pi or any Linux host into a network-wide ad and tracker blocker. Every device on your network gets blocking automatically through DNS, no browser extension needed: queries hit Pi-hole first, blocked domains get a null response, everything else forwards to your upstream resolver. The skill covers the Docker install (recommended, with a pinned release tag and a compose file), blocklist management, DNS-over-HTTPS upstream resolvers for encrypted queries, DHCP integration so Pi-hole hands out addresses itself, local DNS records like nas.home.lan, and troubleshooting the classic failure modes (devices losing internet after install, broken resolution paths). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: you need a Linux host or Raspberry Pi plus router admin access to point DNS at it; a misconfigured DNS server takes your whole network offline, so change one device first and keep your old DNS settings written down. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-homelab-pihole-dns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-homelab-pihole-dns
- Category: Homelab
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/homelab-pihole-dns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
