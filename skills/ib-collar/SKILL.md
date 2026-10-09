<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-collar
description: "A tactical collar report for a PMCC position in your IB account before earnings: put choices by..."
---

# IB Tactical Collar

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Connected to the live port, this skill reads a real brokerage account holding real money, and the hedge it recommends costs real premium: a collar report is a decision worksheet, not protection you already own, and skipping or mispricing the hedge around earnings carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: a tactical collar strategy report for one PMCC position in your Interactive Brokers account, built for the specific moment the strategy is fragile, the run into earnings or another high-risk event. The script reads your actual position (the long LEAPS call with its strike, expiry, quantity and cost, plus your short calls), checks the structure's health (a proper PMCC has the short strikes above the long strike; a broken one, where a drop has pushed the long call out of the money, needs margin for its shorts), pulls the next earnings date and the days remaining, and prices protective puts at several durations with their profit and loss under gap up, flat and gap down scenarios, set against what the unprotected LEAPS loses on a 10 or 15 percent drop or gains on a 10 percent rise. The agent then writes the full report from the repo's template: position summary, health check, earnings risk, put duration comparison (short-dated puts are cheap with more gamma but no salvage on a gap up, medium-dated two to four weeks balance cost and...

- Listing: https://theskillharbor.com/products/ib-collar
- Fiche en français: https://theskillharbor.com/fr/products/ib-collar
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-collar/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
