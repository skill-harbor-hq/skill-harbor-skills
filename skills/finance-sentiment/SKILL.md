<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: finance-sentiment
description: "Normalized stock sentiment across Reddit, X, financial news and Polymarket from one API: buzz..."
---

# Finance Sentiment

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Social buzz is a measure of attention, not of value: a crowded, bullish feed can sit on top of a falling stock, and acting on sentiment alone carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: a read-only reader that fetches normalized stock sentiment from the Adanos Finance API instead of scraping raw social feeds. For one ticker or a batch of up to ten, it pulls the same four fields from each source, Reddit, X.com, financial news and Polymarket: a buzz score out of 100, a bullish percentage, a volume count (mentions for Reddit, X and news, trade count for Polymarket) and a trend direction, over a lookback window that defaults to seven days. That normalization is the point: it lets the agent answer whether Reddit and X agree on a name, which ticker is hottest on each platform, or how many Polymarket bets are active, and then synthesize the cross-source view as aligned bullish, aligned bearish or mixed and diverging. A deeper per-ticker detail endpoint exists for follow-up questions. From the himself65/finance-skills repository (MIT). Honest caveats: it needs an Adanos API key, kept in the ADANOS_API_KEY environment variable and sent as an X-API-Key header, never in the chat; a source with no data is reported as no data, not as neutral or bearish, and the skill itself warns against overstating precision; sentiment is a research signal about...

- Listing: https://theskillharbor.com/products/finance-sentiment
- Fiche en français: https://theskillharbor.com/fr/products/finance-sentiment
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/data-providers/skills/finance-sentiment/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
