<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-prompt-optimizer
description: "Advisory prompt analysis for Muse: paste a draft prompt, get intent detection, missing-context..."
---

# Prompt Optimizer

Curated by Skill Harbor: a prompt optimizer that works strictly as an advisor, never as an executor. Paste a draft prompt and it runs a six-phase analysis: project detection (CLAUDE.md, tech stack), intent detection, missing-context diagnosis, matching to ECC commands, skills, and agents, then outputs a complete optimized prompt you can paste and run yourself, with the diagnosis and rationale attached. It refuses to switch into implementation mode even if you say "just do it"; if you want execution, you make a normal task request instead. It also knows its boundaries: requests to optimize code or performance are refactoring tasks, not prompt tasks, and it says so. Original concept by community member YannJY02, via @affaan-m, listed here with credit to its creators. From the affaan-m/ECC repository (MIT). Honest caveats: advice quality depends on the draft you give it; a vague one-liner cannot become a precise spec by magic; always read the optimized prompt before running it. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-prompt-optimizer
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-prompt-optimizer
- Category: Prompting
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/prompt-optimizer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
