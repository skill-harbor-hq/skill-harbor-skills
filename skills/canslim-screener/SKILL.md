<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: canslim-screener
description: "Screen US growth stocks with William O'Neil's full CANSLIM method: seven scored components, a 0 to..."
---

# CANSLIM Screener

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Trading involves real risk of loss, and a high screener score is not a promise of returns. Curated by Skill Harbor: a full implementation of William O'Neil's CANSLIM growth-stock system, all seven components scored with the original weights: Current earnings (15%), Annual growth (20%), Newness and new highs (15%), Supply and demand (15%), Leadership via multi-period weighted relative strength (20%), Institutional sponsorship (10%), and Market direction (5%). Stage 1 pulls data from the Financial Modeling Prep (FMP) API with a Finviz fallback for institutional ownership, progressively filters the universe to save API calls, and produces a 0 to 100 composite score with interpretation bands (Exceptional at 80+, Strong at 70+) in JSON and markdown; the Market component gates the results in bear markets. It runs on Python 3.9+ with requests, beautifulsoup4, and lxml. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: an FMP API key is required (the free tier's 250 calls per day covers roughly 35 stocks; screening more needs FMP's paid Starter tier at $29.99/month, the skill itself is free). CANSLIM is a momentum-growth method with a long history and real drawdowns; it is not suited to value or income investing, and the method's own rules say to raise cash when the market component turns hostile. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/canslim-screener
- Fiche en français: https://theskillharbor.com/fr/products/canslim-screener
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/canslim-screener/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
