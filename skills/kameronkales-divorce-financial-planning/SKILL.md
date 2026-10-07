<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: kameronkales-divorce-financial-planning
description: "Model a divorce's money split: QDRO, after-tax equalization, buyout vs. sell."
---

# Divorce Financial Planning Skill for Muse

Models the financial split of a divorcing household: QDRO division of 401(k)/pension/IRA accounts, after-tax equalization that discounts each award to its real value (a dollar of Roth is not a dollar of traditional), the equalizing cash payment for a truly even settlement, pension present-value split, home buyout vs. §121-split sale comparison, post-2019 alimony after-tax cost, the MFJ-to-single bracket shift, and divorced-spouse Social Security eligibility under the 10-year marriage rule. Every assumption the engine applies is read back so you can correct it. Discovered via skills.sh. Honest note: the skill carries no math itself — all calculations run server-side through the planfi MCP, which you must connect (`claude mcp add --transport http planfi https://ai.planfi.app/mcp/free`); it's free for personal use (an allowance with no key needed; commercial use is paid). All content is US-centric (QDRO, §121, TCJA alimony rules); planning estimates only — confirm the actual split with a QDRO attorney and tax professional. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/kameronkales-divorce-financial-planning
- Fiche en français: https://theskillharbor.com/fr/products/kameronkales-divorce-financial-planning
- Category: Family
- Price: Free
- Verification: unverified
- Source repo: https://github.com/kameronkales/planfi-skills/blob/main/skills/divorce-financial-planning/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
