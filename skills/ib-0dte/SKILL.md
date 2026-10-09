<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-0dte
description: "Find 0DTE credit spreads on your IB account, and place them only on an explicit execute flag: EMA..."
---

# IB 0DTE Credit Spreads

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This is the highest-risk skill in this catalogue batch: 0DTE options expire the same day, a credit spread can move from a small credit to its full maximum loss in minutes, and this skill can place real orders on a real Interactive Brokers account when its execute flag is passed. Stops reduce average losses but cannot guarantee an exit price in a fast move or a gap, so the budget-capped maximum loss is the real floor. Paper trading first is not a suggestion here, it is the only sane way to learn this tool. No output here is a promise of return. Curated by Skill Harbor: a finder and executor for zero-days-to-expiration credit spreads (bear call, bull put or iron condor) on cash-settled indices (SPX, NDX, RUT, VIX and others) and any optionable stock or ETF, with all data from IB. The default route is a regime strategy: it reads 30-minute IB bars, checks the volatility index (VXN for NDX and QQQ with a cutoff of 35, VIX otherwise with a cutoff of 20, and both the intraday reading and the prior close must pass), takes the direction from the last EMA 9/21 cross, and skips the trade entirely when the regime fails or the volatility reading is unavailable; two optional confirmation gates (a red-red bar check and a time gate anchored to the morning bars) are off by default. A manual route lets you name the spread type directly. Either way the finder ranks candidates by expected value with the...

- Listing: https://theskillharbor.com/products/ib-0dte
- Fiche en français: https://theskillharbor.com/fr/products/ib-0dte
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib_0dte/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
