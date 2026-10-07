<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: 2dmurali-review-loop-skill-review-loop
description: "Iterate on work with a critic subagent scoring 1–10 until a quality gate is met"
---

# Review Loop: worker–reviewer iteration cycle

Curated by Skill Harbor — a short pointer to @2dmurali's iterative worker–reviewer workflow: do the work, spawn a separate critic subagent (fresh context, no anchoring) that scores it 1–10 with actionable feedback, revise, and repeat until a quality gate (default 8/10, 2–4 loops) is met — with reviewer-power rules, escalation signals, a reviewer prompt template and a review-criteria table by task type (code, specs, refactors, APIs, migrations…). Honest caveats: **no license declared in the repository — license unknown** (its footer says MIT, but no license file was found), so this is a short fiche linking to the source, without reusing its content; requires a platform that supports subagent spawning; each loop costs extra tokens, so set tight min/max bounds. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/2dmurali-review-loop-skill-review-loop
- Fiche en français: https://theskillharbor.com/fr/products/2dmurali-review-loop-skill-review-loop
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/2dmurali/review-loop-skill/blob/main/review-loop/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
