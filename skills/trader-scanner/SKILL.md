<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: trader-scanner
description: "Scan thousands of charts for setups, before the open and intraday."
---

# trader-scanner

Trader Scanner is the first step of a day trade. It builds the universe with the universe command, downloading nasdaqlisted.txt and otherlisted.txt from Nasdaq Trader and keeping plain tickers that pass its include and exclude rules, while leaving out test issues, ETFs, NextShares, preferred shares, units, warrants and rights. On the October 19 2026 files this kept 5,943 symbols.

The daily scan, run before the open, checks daily closes: 20-day closing-high breakout, bull flag, reclaim of the 20-day average, oversold, and oversold bounce. Yahoo's spark endpoint returns closes for 20 symbols per request, so 5,942 symbols take 298 requests. The intraday scan, run after 9:50 AM ET, checks opening-range breakouts on 5-minute bars: the first completed 5-minute bar to close above the range high, with a two-stage check that prints PARTIAL when it skips candidates beyond its confirm limit. Hits are listed most traded first, by price times volume.

Limits as written in the SKILL.md: a scan is a list of charts that match a rule, not a list of stocks to buy, and a setup on a chart is not a prediction. Most people who day trade lose money, and the scanner does not change that. Partial results are always said as partial, never rounded up to "the whole market". A hit is stale once the price has moved on, so it must be re-run before acting on it. It never places, sizes or checks an order, never says which stock to buy, never calls data real time, and never promises that a setup works. It...

- Listing: https://theskillharbor.com/products/trader-scanner
- Fiche en français: https://theskillharbor.com/fr/products/trader-scanner
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Jakeschincariol/day-trader-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
