<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: market-breadth-analyzer
description: "A 0 to 100 market breadth health score from six components, computed from free public data: is the..."
---

# Market Breadth Analyzer

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A breadth score is market context, not a buy or sell signal, and trading involves real risk of loss. Curated by Skill Harbor: a quantitative answer to the question "is this rally actually healthy?" Instead of eyeballing index charts, it scores market breadth from 0 (critical weakness) to 100 (maximum health) across six components measuring how broadly stocks participate in the move: advance-decline behavior, participation rates, and related internals. The data is the author's own publicly published dataset, two CSV files hosted on GitHub Pages with roughly 2,500 rows reaching back to 2016, so no API key and no data subscription are needed. The included Python script (3.9+, requests only) fetches the detail and summary files, checks data freshness and warns if the data is more than 5 days old, computes each component (redistributing weights automatically if a component has no data), classifies the composite into health zones, tracks the score's history and trend (improving, deteriorating, stable), and writes JSON and markdown reports. Traders use it as an exposure gauge: strong breadth supports staying invested, deteriorating breadth argues for caution. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: the whole skill depends on one maintainer's public dataset staying updated; the freshness warning is your signal if it ever stalls. Breadth describes the...

- Listing: https://theskillharbor.com/products/market-breadth-analyzer
- Fiche en français: https://theskillharbor.com/fr/products/market-breadth-analyzer
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/market-breadth-analyzer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
