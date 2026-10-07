<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-homelab-network-setup
description: "Plan a home or homelab network that grows: gateways, IP ranges, DHCP, DNS, cabling, and beginner..."
---

# Homelab Network Setup

Curated by Skill Harbor: a practical network-planning skill for home and small-lab networks, written to prevent the rebuild everyone does once. It starts by separating device roles cleanly (modem or ONT, then gateway or router for NAT, firewall, DHCP, DNS and inter-VLAN routing, then managed switch, then access points on wired backhaul, then servers and NAS on stable addresses, then clients and IoT on DHCP pools), and it picks the gateway to match the operator rather than the feature checklist: ISP router for basic internet only, UniFi for a managed home network, OPNsense or pfSense for flexible homelab control, MikroTik for advanced users, Linux router for tinkerers. The IP plan is opinionated where it matters: avoid 192.168.1.0/24 when VPNs are in play (it collides with hotels, offices, and ISP routers), use one /24 per trust zone (trusted clients, IoT and media, servers and NAS, guest Wi-Fi, management), reserve .1 for the gateway and .2 through .49 for infrastructure, and use home.arpa for local names since it is reserved for home networks. It covers DHCP reservations for anything you SSH into, DNS strategy up to Pi-hole deployment, cabling and PoE guidance, and a catalog of anti-patterns: double NAT without documentation, dynamic addresses for the NAS, consumer routers repurposed as APs with DHCP still on, flat networks mixing cameras and laptops on one trust boundary. Two worked examples included: a beginner upgrade that keeps the ISP router, and a VLAN-ready plan that...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-homelab-network-setup
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-homelab-network-setup
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/homelab-network-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
