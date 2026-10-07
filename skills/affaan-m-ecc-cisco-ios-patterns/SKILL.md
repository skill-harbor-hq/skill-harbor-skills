<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-cisco-ios-patterns
description: "Review Cisco IOS configs and plan safe change windows — written in Japanese"
---

# Cisco IOS/IOS-XE review patterns

Curated by Skill Harbor — @affaan-m's Cisco IOS/IOS-XE review patterns: read-only evidence collection (`show version`, `show inventory`, `show running-config` sections, `show ip access-lists`, `show spanning-tree`, `show ip route`...), mode reference (user, enable, config, interface modes), wildcard-mask vs subnet-mask tables with an ACL example, config-hierarchy and interface-hygiene notes, and a safe change-window workflow (capture state read-only, review the exact candidate config, confirm management access isn't locked out, apply the smallest change in a maintenance window, re-read state and only then save with `copy running-config startup-config`). Honest caveats: **the skill is written in Japanese** (lives under `docs/ja-JP/`); patterns are review guides, never production changes — verify platform, interface names, current config, rollback path and out-of-band access on the real device before touching anything; never dump full configs (they may contain secrets, customer names, private topology) into tickets; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-cisco-ios-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-cisco-ios-patterns
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/docs/ja-JP/skills/cisco-ios-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
