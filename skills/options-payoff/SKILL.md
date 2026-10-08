<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: options-payoff
description: "An interactive payoff chart for any options strategy: expiry profit and loss plus the Black-Scholes..."
---

# Options Payoff Chart

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Options carry a real risk of loss, including the full premium paid, and a payoff chart shows math, not a recommendation. Curated by Skill Harbor: an interactive payoff visualizer for options positions. Describe a strategy in plain words, paste strikes and premiums, or share a broker screenshot (IBKR, TastyTrade, Robinhood), and it detects the structure (vertical, calendar, diagonal, and ratio spreads, butterflies, condors and iron condors, straddles, strangles, covered calls, protective or naked puts, or a custom multi-leg mix), then renders a chart with two curves: the expiry payoff and the Black-Scholes theoretical value at the current time and volatility. Sliders let you move strikes, premium, quantity, implied volatility, days to expiry, the risk-free rate, and the spot price, while stat cards update max profit, max loss, breakevens, and the theoretical profit or loss at spot. Missing details are filled with stated defaults rather than silently invented, and the spot comes from a live quote where possible instead of being read off strike labels. From the himself65/finance-skills repository (MIT). Honest caveats: the skill is built for a chat surface that can render an interactive HTML widget; without one, your agent can still generate the same chart as a standalone HTML file to open in a browser. Theoretical values rest on Black-Scholes assumptions (constant volatility, no early...

- Listing: https://theskillharbor.com/products/options-payoff
- Fiche en français: https://theskillharbor.com/fr/products/options-payoff
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/market-analysis/skills/options-payoff/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
