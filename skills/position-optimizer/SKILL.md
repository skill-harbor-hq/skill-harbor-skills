<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: position-optimizer
description: "Improve a working strategy at the capital layer only: Kelly fractions, volatility targeting..."
---

# Position Optimizer

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Position sizing is where accounts die: leverage multiplies losses as faithfully as gains, and martingale-style recovery, even capped, can turn a drawdown into a liquidation. This skill tests those models in backtests; no backtest makes a dangerous sizing model safe. Curated by Skill Harbor: a specialist persona prompt from DaviddTech's ai-trading-agent repo that works only on the capital allocation layer of a strategy that already has an edge. It is forbidden from touching entry signals, exit signals, indicator logic or regime filters; what it may tune is size, leverage, risk per trade, Kelly fraction, volatility-adjusted sizing, drawdown throttling, equity-curve scaling, maximum exposure and stop-trading conditions. It benchmarks a fixed-risk baseline, then tests fixed leverage (2x to 10x), fractional Kelly from 10% to 100% (with the explicit warning that full Kelly is never assumed safe), volatility-adjusted and drawdown-aware sizing, anti-martingale scaling, a controlled martingale recovery model with strict survival rules (bounded steps, max loss cap, liquidation checks, automatic shutdown; unlimited doubling and hidden blown tests are forbidden), and a hybrid model. Variants are backtested through the Trader Dev MCP tools and ranked by return-to-drawdown ratio, survival probability and liquidation safety before net profit. From the DaviddTech/ai-trading-agent repository (MIT)....

- Listing: https://theskillharbor.com/products/position-optimizer
- Fiche en français: https://theskillharbor.com/fr/products/position-optimizer
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/DaviddTech/ai-trading-agent/blob/main/skills/position-optimizer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
