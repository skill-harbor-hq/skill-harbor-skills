<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: strategy-backtest
description: "Turn a trading idea into a YAML strategy, backtest it with realistic costs, and read expectancy..."
---

# Strategy Backtest

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A backtest describes one simulated past; it cannot certify that a strategy will make money, and most backtested ideas fail live. Curated by Skill Harbor: the backtesting workflow of the Weaxs stock-analysis-plugin. You express a strategy in a small YAML language (entry and exit conditions over indicators such as RSI, moving averages, MACD, volume ratio, and Bollinger position, combined with AND or OR logic, plus stop-loss, take-profit, position size, and cost settings for slippage, commission, and stamp tax), then run it over a chosen symbol and date range with the repo's tools/backtest.py. The report leads with expectancy alongside win rate and payoff ratio, then max drawdown, losing streaks, trade count, and average holding period, with the actual cost assumptions printed from the run itself. The workflow insists on separate in-sample and out-of-sample windows, treats parameter changes as hypotheses to test rather than improvements to accept, caps optimization at three rounds, and only optimizes when you explicitly ask. From the Weaxs/stock-analysis-plugin repository (MIT). Honest caveats: the source SKILL.md is written in Chinese and the default fee examples are A-share conventions (the stamp tax line simply does not apply on many markets); settlement rules, price limits, and corporate-action adjustments may not be simulated, and the report is supposed to list what was left out; a...

- Listing: https://theskillharbor.com/products/strategy-backtest
- Fiche en français: https://theskillharbor.com/fr/products/strategy-backtest
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Weaxs/stock-analysis-plugin/blob/main/skills/strategy-backtest/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
