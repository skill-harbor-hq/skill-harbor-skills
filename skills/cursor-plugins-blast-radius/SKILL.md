<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: cursor-plugins-blast-radius
description: "Assess what a diff could break beyond the callers — find the one safety fact, climb the confidence..."
---

# Blast-radius analysis: prove a change is safe by running code, not writeups

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @cursor's blast-radius methodology for reviewing a diff you don't trust — don't hand back a writeup that merely sounds right; find the one or two facts the change's safety depends on, and for each fact climb the confidence ladder (you said so → you pointed at a real file:line → you walked the failure step by step → you ran real code → you reproduced it in the running app), stating honestly where each one stopped. Then prove the key fact with a small script or test that calls the real code and fails loud if you're wrong — and for big changes, run it as an arena (several models, merge the answers). Companion to the how/why skills in the same repository — not bundled here. Honest caveats: methodology only, no tooling — the agent must be able to run code against the repo; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/cursor-plugins-blast-radius
- Fiche en français: https://theskillharbor.com/fr/products/cursor-plugins-blast-radius
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/cursor/plugins/blob/main/pstack/skills/blast-radius/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
