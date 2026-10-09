<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: spread-analysis
description: "Price a vertical spread, straddle, strangle, or iron condor before you trade it: net debit or..."
---

# Option Spread Analysis

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Defined-risk on paper is still real risk in a live account, and multi-leg trades carry assignment and execution risks a worksheet cannot remove. Curated by Skill Harbor: a pre-trade worksheet for multi-leg option strategies. Name the strategy (vertical spread, straddle, strangle, or iron condor), the ticker, the expiry, and the strikes, and it prices the structure from the Yahoo Finance chain: net debit or credit, maximum profit, maximum loss, breakeven price or prices, and an estimated probability of profit derived from implied volatility, with an explanation of the risk, the reward, and when the strategy fits. This is the math traders usually do inside a broker platform's analyzer, done in chat before any order exists: compare a defined-risk vertical against a wider iron condor, see exactly where you stop making money, and what the trade costs if you are simply wrong. It runs as a Python script (scripts/spreads.py, needs pandas and yfinance) from the staskh/trading_skills repo. From the staskh/trading_skills repository (MIT). Honest caveats: the probability of profit is an IV-based model estimate, not a real-world frequency, and the math ignores commissions, bid-ask slippage, early assignment, and dividend risk on short legs; Yahoo quotes can be delayed, so recheck prices in your broker before trading. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/spread-analysis
- Fiche en français: https://theskillharbor.com/fr/products/spread-analysis
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/spread-analysis/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
