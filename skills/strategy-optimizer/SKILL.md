<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: strategy-optimizer
description: "Fork a promising strategy, change it for one stated reason, and keep the fork only if it survives..."
---

# Strategy Optimizer

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Optimization is the easiest way to manufacture a beautiful backtest that means nothing; this skill's whole discipline exists to refuse exactly that, and even a disciplined fork can fail live. Curated by Skill Harbor: the improvement specialist of DaviddTech's ai-trading-agent repo, a persona prompt that searches the Trader Dev strategy library for systems showing signs of life (a positive profit factor with poor drawdown, good entries with poor exits, strength on one pair but untested elsewhere), forks one, reads its Pine Script until the logic is fully understood, and only then changes it, under a written improvement hypothesis. Every addition must solve a specific weakness: regime detection, volatility filtering, entry timing, exit structure, stop placement, cooldowns, false breakout protection. Indicator soup is explicitly out. The fork is backtested against the original across multiple random crypto pairs from the top 100 Bybit listings and multiple timeframes (15m to 4h), compared on profit factor, drawdown, win rate, trade count and long/short splits, and checked for the usual lies: too few trades, one outlier trade carrying the result, repainting, future-looking logic, collapse outside the original market. The cycle can run inside a 15-minute agent loop and ends with a structured report and a keep, reject or iterate decision; dead strategies are to be abandoned, not optimised...

- Listing: https://theskillharbor.com/products/strategy-optimizer
- Fiche en français: https://theskillharbor.com/fr/products/strategy-optimizer
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/DaviddTech/ai-trading-agent/blob/main/skills/strategy-optimizer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
