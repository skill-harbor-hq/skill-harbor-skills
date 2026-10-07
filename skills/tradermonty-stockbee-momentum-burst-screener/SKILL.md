<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: tradermonty-stockbee-momentum-burst-screener
description: "Screen US stocks for short-term breakout setups"
---

# Stockbee Momentum Burst Screener Skill for Muse

Turns Muse into a disciplined stock screener for Stockbee-style short-term Momentum Burst setups: it runs a three-mode workflow (full universe scan, explicit symbols, or offline OHLCV JSON) detecting 4% breakouts, dollar breakouts, and range expansions, then scores each candidate on setup quality — trigger strength, volume expansion, base contraction, close location, risk distance to the trigger-day low — with failure filters and A/B/C ratings, handing survivors off to chart validation and position sizing. Discovered via skills.sh. Honest note: it is a candidate-generation workflow, not a signal service and not auto-execution — US equities only, and the scripted path needs Python plus an FMP API key (a free tier exists) or your own OHLCV data via the no-API path; screening candidates is research, not financial advice, and swing trading real money carries real risk. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/tradermonty-stockbee-momentum-burst-screener
- Fiche en français: https://theskillharbor.com/fr/products/tradermonty-stockbee-momentum-burst-screener
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
