<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: scanner-pmcc
description: "Score stocks for Poor Man's Covered Call setups: LEAPS and short-call delta, liquidity, spreads..."
---

# PMCC Scanner

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A PMCC is a leveraged diagonal spread, not a cheap stock substitute: the LEAPS can lose most of its value, the short call caps your upside and can be assigned, and a high scanner score says the options are tradable, not that the trade will profit. Trading it carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: a scanner that scores symbols for Poor Man's Covered Call suitability, the strategy that pairs a deep in-the-money LEAPS call (delta about 0.80, at least 270 days out by default) with a short out-of-the-money call (delta about 0.20) sold against it. Every candidate is scored on a published scale (maximum 14, theoretical range from minus 8 to 14): closeness of both legs to their target deltas, volume and open interest on both legs, bid-ask spread percentages, an implied volatility band that pays best between 25 and 50 percent, the period and annualized yield, trend checks (price against the 50-day average, RSI, MACD), and the distance to the next earnings date, with penalty-only deductions for missing weekly options, thin strike density and tiny short premiums. The output gives the chosen LEAPS and short legs with strike, delta, bid, ask and volume, the net debit and capital required, and a full score breakdown where every component shows its points and its explanation, so a low score can be traced to the exact failing test. A notable craft...

- Listing: https://theskillharbor.com/products/scanner-pmcc
- Fiche en français: https://theskillharbor.com/fr/products/scanner-pmcc
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/scanner-pmcc/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
