<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ma-crossover
description: "Golden crosses and death crosses, graded: which MA pair crossed, how strong the signal looks, and..."
---

# Moving Average Crossover

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Crossovers are lagging signals by construction, and in a sideways market they whipsaw; treat every cross as a prompt to look closer, not as an order. Curated by Skill Harbor: a focused moving-average crossover workflow from the Weaxs stock-analysis-plugin. It gathers 120 days of candles and indicators, then reads three crossover pairs (MA5 over MA10 for the short term, MA10 over MA20 for the medium term, MA20 over MA60 for the longer trend) and grades the latest cross instead of just reporting it: a cross that follows a real decline or base, arrives on expanding volume, opens at a clear angle, and resonates with a MACD cross scores high; a cross inside choppy range trading, on shrinking volume, with the averages gluing back together right away scores low. It also reports the full alignment of the averages, the strongest pattern (several averages crossing together after a tight consolidation), and the levels where the averages themselves act as dynamic support or resistance. From the Weaxs/stock-analysis-plugin repository (MIT). Honest caveats: the source SKILL.md is written in Chinese; the method is completely standard technical analysis, which also means it carries the well-known limits of the genre, namely late entries and false signals in ranges; nothing in it adapts the parameters to a specific market's volatility. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/ma-crossover
- Fiche en français: https://theskillharbor.com/fr/products/ma-crossover
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Weaxs/stock-analysis-plugin/blob/main/skills/ma-crossover/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
