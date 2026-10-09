<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-trailing-stop
description: "Server-side trailing stops for stocks and naked LEAPS in a real Interactive Brokers account: native..."
---

# IB Trailing Stop Manager

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. This skill connects to a REAL Interactive Brokers account and, in execute mode, it can place, replace and cancel real trailing stop orders on that account: a trail set too tight can sell you out of a position on ordinary noise, a trail set too wide protects little, there is a real risk of loss on every position it touches, and no output here is a promise of return. Curated by Skill Harbor: the IB trailing stop manager of staskh/trading_skills. Use it to protect stocks and naked LEAPS with IB native TRAIL orders: once placed, Interactive Brokers itself adjusts the stop trigger upward as the price climbs and locks it as the price falls, so the protection runs server-side even when your machine is off. The reference price is the higher of the current price and your average cost, so a trail never starts below entry unless forced mode deliberately uses the current price to re-arm after a drawdown; the initial stop is the reference minus the trail percentage (20 percent by default) or minus a fixed dollar amount. Existing TS_ trail orders are preserved by default, precisely because IB has been ratcheting them since placement and replacing one would reset the tracked high; forced mode cancels and replaces them, and orphan trails for gone positions are cancelled in execute mode. PMCC positions are intentionally excluded: a standalone trailing stop on the PMCC long leg would break the hedge at...

- Listing: https://theskillharbor.com/products/ib-trailing-stop
- Fiche en français: https://theskillharbor.com/fr/products/ib-trailing-stop
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-trailing-stop/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
