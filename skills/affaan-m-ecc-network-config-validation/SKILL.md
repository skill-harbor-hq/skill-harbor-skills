<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-network-config-validation
description: "Pre-deployment checks for router and switch configs: dangerous commands, duplicate IPs, subnet..."
---

# Network Config Validation

Curated by Skill Harbor: a network config validation skill that pre-flights router and switch configurations before they touch production. It validates in a deliberate order: destructive commands first (reload, erase startup/nvram/flash, removing routing processes or interfaces, zeroizing SSH keys), then credential and management-plane exposure, then duplicate IP addresses and overlapping subnets, then stale references to ACLs, route-maps, prefix-lists, and interfaces that are referenced but never defined, and finally operational hygiene (NTP, timestamps, remote logging, banners). It includes ready-to-use Python snippets for dangerous-command detection and duplicate-IP/subnet-overlap checks, aimed at Cisco IOS and IOS-XE style configs and at auditing script-generated config. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: regex checks are useful pre-flight warnings, not a complete parser; final approval still needs a network engineer to review intent, platform syntax, and rollback steps; never paste real device credentials into a chat. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-network-config-validation
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-network-config-validation
- Category: Networking
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/network-config-validation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
