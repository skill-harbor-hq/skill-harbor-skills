<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: longbridge-derivatives
description: "Option chains, Greeks and implied volatility for US and HK names, plus Hong Kong warrants and..."
---

# Longbridge Derivatives (Options and Warrants)

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Options and warrants are leveraged instruments that can expire worthless; a payoff diagram shows the shape of a position, never its probability. Curated by Skill Harbor: the derivatives skill of the Longbridge platform, published by the broker itself, for Hong Kong and US markets. Through the Longbridge CLI it serves option quotes, full option chains, option volume and open interest statistics, the Greeks (Delta, Gamma, Theta, Vega) and implied volatility, plus the Hong Kong warrant market: call and put warrants, callable bull and bear contracts (CBBC), warrant lists and issuer lists. Four frameworks organize the analysis: strategy selection across covered calls, protective puts, straddles, strangles and bull or bear spreads; payoff analysis with diagrams, breakeven points, maximum profit and loss, and Greeks sensitivity; implied volatility analysis comparing IV to historical volatility, reading the IV percentile rank and the volatility smile and skew; and an advanced layer covering the volatility surface, dynamic delta hedging, and calendar and diagonal spreads. The data commands are public with no login required, although US options data requires US market access on the feed. From the longbridge/skills repository (MIT). Honest caveats: chain data is a snapshot of listed contracts and can be thin or wide on illiquid names, quoted Greeks depend on the pricing model and inputs behind...

- Listing: https://theskillharbor.com/products/longbridge-derivatives
- Fiche en français: https://theskillharbor.com/fr/products/longbridge-derivatives
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/longbridge/skills/blob/main/skills/longbridge-derivatives/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
