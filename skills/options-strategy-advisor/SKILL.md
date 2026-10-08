<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: options-strategy-advisor
description: "Simulate options strategies with Black-Scholes pricing and Greeks: covered calls, protective puts..."
---

# Options Strategy Advisor

⚠️ **Trading warning / Avertissement trading** : informational and educational only, not investment advice. Options are leveraged instruments that can expire worthless; you can lose your entire premium. Curated by Skill Harbor: an options strategy workbench built on theoretical models rather than live market data subscriptions. Its Black-Scholes scripts compute theoretical option prices and the Greeks (delta, gamma, theta, vega), and its simulators draw profit and loss profiles for the major strategy families: income strategies like covered calls and cash-secured puts, protection like protective puts and collars, directional spreads, and volatility plays such as straddles and iron condors, including earnings-based setups that pull upcoming earnings dates into the analysis. Each simulation surfaces max profit, max loss, breakevens, Greeks exposure, and position-sizing guidance, with plain-language explanations aimed at learning how a strategy behaves before any real order exists. It runs on Python 3.9+ with numpy, scipy, and requests; a Financial Modeling Prep (FMP) API key is optional and only used to fetch current prices, historical volatility, dividends, and earnings dates automatically, otherwise you type the inputs in yourself. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: theoretical Black-Scholes prices are model estimates, not executable market quotes; real fills include bid-ask spreads, liquidity, and assignment risk that a simulator...

- Listing: https://theskillharbor.com/products/options-strategy-advisor
- Fiche en français: https://theskillharbor.com/fr/products/options-strategy-advisor
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/options-strategy-advisor/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
