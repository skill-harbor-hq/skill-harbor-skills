<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: backtest-expert
description: "Systematic backtesting methodology that hunts for strategies that break the least: robustness..."
---

# Backtest Expert

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A strategy that survives backtest stress tests can still lose money live; past simulated performance never guarantees future results. Curated by Skill Harbor: a professional backtesting methodology whose goal is inverted from the usual one: find strategies that "break the least" under pessimistic conditions, not strategies that "profit the most" on paper. The workflow forces discipline at every step: state the edge as a one-sentence hypothesis (if you cannot, stop), codify entry, exit, sizing, filters, and universe with zero discretion, run the initial test over at least 5 and preferably 10+ years across bull, bear, and high and low volatility regimes with realistic commissions and conservative slippage, then spend most of the time stress testing: stop and target parameters varied from 50% to 150% of baseline looking for stable plateaus instead of narrow spikes, entry and exit timing shifted, slippage inflated to 1.5 to 2 times typical estimates, and worst-case fills modeled. A dedicated bias-prevention pass hunts curve-fitting, look-ahead bias, and survivorship bias, the three classic ways backtests lie. An evaluation script (Python 3.9+) scores user-provided metrics; no API keys and no external data are required, you bring your own data and results. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: this is methodology and evaluation guidance, not a...

- Listing: https://theskillharbor.com/products/backtest-expert
- Fiche en français: https://theskillharbor.com/fr/products/backtest-expert
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/backtest-expert/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
