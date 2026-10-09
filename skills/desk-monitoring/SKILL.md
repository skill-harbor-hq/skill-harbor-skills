<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: desk-monitoring
description: "Watch Hyperliquid markets and your account between trades: the daily desk brief, book checks..."
---

# Desk Monitoring

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Monitoring only reads and alerts; it cannot protect a position by itself, and a watch that silently fails looks exactly like a calm market, which is how accounts get hurt. No alert here is a promise of return. Curated by Skill Harbor: the monitoring skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid. It defines the routines each desk role can own (a daily desk brief led by a plain conclusion about the book, a book check every few hours while positions are open, a funding snapshot, a weekly catalyst calendar refresh and a weekly review), and two ways to watch: polling the info endpoint on a short loop, or WebSocket subscriptions for fills and order updates. The common watch conditions are spelled out with their data source and alert target: price crossing a level, funding flipping sign or passing a threshold, an order filled or cancelled, margin ratio or liquidation distance breaching a bound, a position without a resting stop, the daily loss stop approached or hit, and the exchange unreachable. The safety core is a three-outcome rule: a watch has fired, not fired, or could not tell, and a failed, stale or gapped read must alert as unavailable with the age of the last good value, never as silence. Every watch logs with UTC timestamps, carries a staleness bound, and respects rate limits, because a rate-limited desk is a blind desk. If a condition implies action...

- Listing: https://theskillharbor.com/products/desk-monitoring
- Fiche en français: https://theskillharbor.com/fr/products/desk-monitoring
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/desk-monitoring/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
