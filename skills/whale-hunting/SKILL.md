<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: whale-hunting
description: "Detect institutional-sized options trades for one underlying: a Yahoo chain scan for anomalous..."
---

# Whale Hunting

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A large options trade is not automatically a bullish or bearish bet: it can be a hedge, one leg of a spread, or a closing trade, and the detector cannot tell which; copying flow you cannot interpret carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: a two-step detector for institutional-sized options activity on one underlying. The first step scans the Yahoo Finance chain for contracts whose daily invested dollars are anomalous against the rest of the chain (a standard-deviation threshold, 3.0 by default). The second step, when a Massive API key is available, drills into each candidate with per-second bars and flags the seconds whose invested dollars are outliers (a modified Z-score, 3.5 by default), which is how a single block trade inside a busy contract gets isolated. The output names the source honestly (massive for the per-second pass, yahoo only for the daily fallback), totals the call and put dollars invested with their ratio, and lists each whale event with its time, contract, strike, expiry, volume, transaction count, dollars invested and breakeven; an optional summary aggregates events per contract. The skill's own reading guide is included: a call to put ratio under 0.5 reads bearish, over 2.0 bullish, and a single-transaction event is the strongest signal. It runs as a Python script from the staskh/trading_skills repo, over options...

- Listing: https://theskillharbor.com/products/whale-hunting
- Fiche en français: https://theskillharbor.com/fr/products/whale-hunting
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/whale-hunting/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
