<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: greeks
description: "Delta, gamma, theta, vega, rho, and implied volatility for any option, priced with Black-Scholes..."
---

# Option Greeks

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Greeks and implied volatility are model outputs, not predictions, and an option can lose its entire value. Curated by Skill Harbor: a focused calculator that prices an option's sensitivities with the Black-Scholes model. Give it a spot price, a strike, a call or put flag, and an expiry date or a number of days to expiry, and it returns delta, gamma, theta, vega, and rho as clean JSON. Pass the option's market price and it also solves for implied volatility by Newton-Raphson inversion, so you can compare the market's expectation against your own volatility view; you can override the volatility or the risk-free rate (5 percent by default), and price the contract as of a past or future date to see how time decay alone moves the numbers. It runs as a small Python script (scripts/greeks.py, needs scipy) from the staskh/trading_skills repo. From the staskh/trading_skills repository (MIT). Honest caveats: Black-Scholes assumes European-style exercise, constant volatility, and no dividends, so American options, dividend payers, and early-exercise risk will differ from these figures; the output is only as good as the spot, price, and rate you feed it; nothing here connects to a broker or a live quote feed. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/greeks
- Fiche en français: https://theskillharbor.com/fr/products/greeks
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/greeks/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
