<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: risk-assessment
description: "Volatility, beta, 95 and 99 percent VaR, max drawdown, and Sharpe for any stock, with a dollar VaR..."
---

# Risk Assessment

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Risk metrics describe the past; they do not cap what a position can lose tomorrow. Curated by Skill Harbor: a risk profile for a stock or a position, computed from its own price history. Over a period you choose (one month to one year), it returns annualized historical volatility, beta against SPY, daily value at risk at 95 and 99 percent, maximum drawdown, and the Sharpe ratio; add a position size in dollars and it also expresses the VaR in dollars for that position, with an explanation of what each metric means and how it bears on position sizing. It is the discipline step most trade ideas skip: before asking how much a position can make, ask how much it has historically swung, how deep it has fallen, and what a bad day at 95 or 99 percent confidence looks like in dollars. It runs as a Python script (scripts/risk.py, needs numpy and yfinance) from the staskh/trading_skills repo. From the staskh/trading_skills repository (MIT). Honest caveats: every metric here is backward-looking, and past volatility, drawdowns, and beta do not bound future losses; VaR is a statistical estimate that real tail events regularly exceed; the data comes from Yahoo Finance and can lag the market. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/risk-assessment
- Fiche en français: https://theskillharbor.com/fr/products/risk-assessment
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/risk-assessment/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
