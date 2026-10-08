<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: vcp-screener
description: "Find Mark Minervini Volatility Contraction Patterns: Stage 2 uptrends forming tight, quiet bases..."
---

# VCP Screener

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Trading involves real risk of loss, and most breakout candidates fail; a detected pattern is not a promise of returns. Curated by Skill Harbor: a screener for Mark Minervini's Volatility Contraction Pattern (VCP), the setup where a stock in a Stage 2 uptrend pauses in a series of progressively tighter pullbacks, volatility dries up, and price coils just under a breakout pivot point. The default run scans the top 100 pre-filtered S&P 500 candidates and flags valid VCPs with their execution state (pre-breakout or breakout); a strict mode returns only those two states. A separate historical mode walks one ticker's multi-year price history (about 5 years by default, up to 10), detects every VCP that ever formed, and attaches forward-outcome statistics to each: breakout, stop-hit, or timeout, days to outcome, maximum gain and loss, which makes it useful for studying how the pattern actually behaved on a name you follow. Results land in timestamped JSON and report files via the skill's Python script. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: a Financial Modeling Prep (FMP) API key is required (the free tier's 250 calls per day is enough for the default screen; the full S&P 500 mode needs FMP's paid tier). Pattern detection is mechanical and produces false positives; Minervini's own method pairs the pattern with strict position sizing and market context...

- Listing: https://theskillharbor.com/products/vcp-screener
- Fiche en français: https://theskillharbor.com/fr/products/vcp-screener
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/vcp-screener/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
