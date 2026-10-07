<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-codehealth-mcp
description: "Structural code health via CodeScene MCP: review before edits, verify score deltas, gate commits..."
---

# Code Health MCP

Curated by Skill Harbor: structural maintainability feedback for AI-assisted coding through the CodeScene MCP server, complementing style linters with design-level health scores and regression gates. The loop is strict: run code_health_review before touching a file to record a baseline score plus the listed code smells, make the smallest change that addresses the task, then run code_health_score after each edit and never mark the task done while the score sits below its baseline. Before every commit, pre_commit_code_health_safeguard blocks regressions; before a PR, analyze_change_set checks the whole branch. Scores run 1 to 10 (green at 9+, yellow from 4 to 8.9, red below 4) with scope rules per range: below 5 means minimal diffs only, 5 to 7 means no broad refactors. Includes a paste-ready AGENTS.md enforcement block and pairing guidance with verification loops, TDD workflows, and security reviews (tests passing does not mean the design is healthy). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: requires the CodeScene MCP server plus your own CS_ACCESS_TOKEN (see the prerequisites in the install prompt); standalone mode needs no paid CodeScene platform account for the four tools. If the MCP is unavailable, the skill instructs to skip the check rather than invent scores. Do not point it at secrets, credentials, or paths you would rather not have analyzed. Skill Harbor never reviews the code, review it yourself...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-codehealth-mcp
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-codehealth-mcp
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/codehealth-mcp/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
