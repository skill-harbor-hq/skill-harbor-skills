<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-skill-scout
description: "Search installed, marketplace, GitHub, and web skill sources before creating a new skill, and vet..."
---

# Skill Scout

Curated by Skill Harbor: a search-before-you-build workflow for skill creation, from the ECC framework but usable by any Claude Code user. Before writing a new skill, it captures intent (the task, trigger conditions, domain, keywords plus synonyms), searches local sources first (~/.claude/skills and marketplace installs via find and grep, preferred because they are already part of your environment), then remote sources (gh search repos and code, at most three targeted web queries), vets every external match (reads the SKILL.md, looks for unexpected shell commands, file writes, network calls, credential handling, package installs, checks repo maintenance), ranks up to 10 candidates, and presents a decision table: use existing, fork or extend, or create fresh. Only create after the user chooses that path or no close match exists. Salvaged from stale community PR #1232 by redminwang. From the affaan-m/ECC repository (MIT). Honest caveats: written for the SKILL.md ecosystem (Claude Code paths, gh CLI); the remote search steps assume your agent has GitHub and web search tooling. It never installs anything by itself; the anti-patterns explicitly forbid installing external skills unread or editing marketplace originals in place. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-skill-scout
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-skill-scout
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/skill-scout/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
