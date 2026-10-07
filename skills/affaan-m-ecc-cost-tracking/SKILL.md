<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-cost-tracking
description: "Report Claude Code token spend by model, session, and date from the local ECC cost metrics log."
---

# Cost Tracking

Curated by Skill Harbor: a reporting skill that reads the JSONL metrics log written by ECC's stop:cost-tracker hook (~/.claude/metrics/costs.jsonl). Each row is a cumulative snapshot per session, so the skill reduces to the latest row per session_id before summing, then reports today's spend vs yesterday, the total across sessions, a by-model breakdown, and session counts, with copy-paste node one-liners for summaries and CSV export. Reporting guidance included (four-decimal formatting under a dollar, two above), plus anti-patterns: never sum every row (double counting), prefer the tracker's estimated_cost_usd over hand-computed pricing, never assume the log exists, never fabricate data. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it reads LOCAL Claude Code/ECC logs on your machine; inside Muse, paste a log excerpt or describe what you need, it cannot reach your machine's files by itself. The log only exists if the ECC cost-tracker hook is enabled; with no log, it tells you so instead of inventing numbers. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-cost-tracking
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-cost-tracking
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/cost-tracking/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
