<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earnings-trade-analyzer
description: "Score recent post-earnings movers with a five-factor system (gap, trend, volume, MA50 and MA200..."
---

# Earnings Trade Analyzer

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Post-earnings momentum is among the most volatile styles of trading; a top grade is a screening result, not a promise of returns. Curated by Skill Harbor: a scorer for post-earnings drift (PEAD) setups that ranks how stocks reacted to their earnings releases in the last few days. Each candidate is scored 0 to 100 across five weighted factors: the size of the earnings gap, the pre-earnings price trend, the volume trend into and after the report, and the stock's position relative to its 200-day and 50-day moving averages, then assigned a letter grade from A (strongest reactions) to D. The default run looks back 2 days and returns the top 20, with options for longer lookback windows, a minimum market-cap filter, and an entry-quality filter. The skill's script is careful about failure honesty: a broken earnings-calendar endpoint, an empty result over days when the market was actually open, or an exhausted API budget each exit as explicit failures rather than a fake "nothing happened today", so scheduled after-close runs do not silently report an empty day. It runs on Financial Modeling Prep (FMP) data. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: an FMP API key is required (the free tier's 250 calls per day covers the default run; larger lookbacks or full screening need FMP's paid tier). Earnings gaps can reverse violently, grades compress a lot of judgment...

- Listing: https://theskillharbor.com/products/earnings-trade-analyzer
- Fiche en français: https://theskillharbor.com/fr/products/earnings-trade-analyzer
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/earnings-trade-analyzer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
