<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: riekelt-principal-engineer-operating-safely
description: "Guards for destructive operations, secrets hygiene and concurrent-session safety — short pointer"
---

# Operating safely on live systems

Curated by Skill Harbor — a short pointer to @riekelt's operating-safely ruleset: the guards for acting on live systems and shared state — look at the target before deleting or overwriting, name the specific instance instead of bulk teardown, per-instance confirmation for destructive operations, secrets hygiene (names and structural checks only, never print values, never decrypt to disk), one writer per file during concurrent sessions, and incident-mode discipline where read-only triage is always allowed but the confirmation bar for destructive operations never drops with urgency. Honest caveats: **no license declared in the repository — license unknown**, so this is a short fiche linking to the source, without reusing its content; the file declares itself as required background for the companion `principal-engineering` skill, so read that too. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/riekelt-principal-engineer-operating-safely
- Fiche en français: https://theskillharbor.com/fr/products/riekelt-principal-engineer-operating-safely
- Category: Engineering
- Price: Free
- Verification: unverified
- Source repo: https://github.com/riekelt/principal-engineer/blob/main/plugins/principal-engineer/skills/operating-safely/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
