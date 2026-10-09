<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ai-hedge-fund
description: "Coordinate a desk of specialist quant prompts that hypothesize, backtest and rank crypto..."
---

# AI Hedge Fund

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This is a research desk, not a money manager: it produces hypotheses, backtests and reports, and a strategy it ranks highly can still fail forward and lose money if traded. Curated by Skill Harbor: the coordinator skill of DaviddTech's ai-trading-agent repo, a short manager prompt that runs an AI quant research workflow end to end. It assigns the work to specialist roles (quant mathematician for brand new strategies, mean reversion engineer, strategy optimizer, position optimizer, plus a risk manager whose job is to reject fragile, overfit or reckless systems, and a report writer) and drives a fixed loop: generate hypotheses, convert them to Pine Script, backtest with the Trader Dev MCP tools, validate across symbols and timeframes, rank by risk-adjusted quality, and prepare candidates for incubation or forward testing. Its operating rules are the honest core of the piece: never trust one backtest, never optimise before a baseline exists, never confuse leverage with edge, never ignore max drawdown, never use martingale without strict caps, never hide failed tests, and never claim production readiness without forward testing. Each cycle ends with a structured report (hypothesis, backtest matrix, best and worst results, robustness and risk scores, verdict, next action). From the DaviddTech/ai-trading-agent repository (MIT). Honest caveats: the skill coordinates the four other DaviddTech...

- Listing: https://theskillharbor.com/products/ai-hedge-fund
- Fiche en français: https://theskillharbor.com/fr/products/ai-hedge-fund
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/DaviddTech/ai-trading-agent/blob/main/skills/ai-hedge-fund/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
