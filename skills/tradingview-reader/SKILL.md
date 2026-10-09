<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: tradingview-reader
description: "Read your own TradingView desktop app: options chains with greeks and per-strike IV, screeners..."
---

# TradingView Reader

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. An options chain, a screener result or a fired alert is raw material for your own judgment, not a recommendation: options and leveraged products carry a real risk of loss, and no reading from your own chart changes that. No output here is a promise of return. Curated by Skill Harbor: a read-only reader that talks to the TradingView desktop app already running on your Mac, through opencli and a Chrome DevTools Protocol attach, using your own logged-in session. That account-bound access is what separates it from headless TradingView tools: full options chains with greeks and bid, ask and per-strike implied volatility, expiries with contract counts, screeners across stocks, crypto, forex, futures and bonds with custom JSON filters, gainers and losers, news headlines and full stories, your watchlists including the colored flag lists, your alerts (active, recently triggered, fired while offline, and the full log), symbol search, current chart state and chart screenshots. The skill is disciplined about volume: filter chains by expiry and strikes around spot instead of dumping thousands of rows, summarize watchlists before listing symbols, and group alerts by status. From the himself65/finance-skills repository (MIT). Honest caveats: this reader is honest about reading a third-party platform through your own account and tools: you need the TradingView desktop app installed on macOS, logged...

- Listing: https://theskillharbor.com/products/tradingview-reader
- Fiche en français: https://theskillharbor.com/fr/products/tradingview-reader
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/data-providers/skills/tradingview-reader/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
