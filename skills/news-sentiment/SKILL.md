<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: news-sentiment
description: "The latest Yahoo Finance headlines for a ticker with publisher, date, and link, plus a short read..."
---

# Stock News Sentiment

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Headlines explain moves after they happen at least as often as they predict them, and a sentiment read is not a trading signal. Curated by Skill Harbor: the recent story flow around a stock, gathered in one question. The skill pulls the latest Yahoo Finance news for a ticker (ten articles by default, adjustable) with headline, publisher, date, and link for each, and adds a brief summary of the overall sentiment across the coverage, so asking what is happening with a stock gets an answer with sourced headlines instead of a bare price move. Paired with the fundamental and technical skills in the same repo, it covers the third leg of a quick review: what the company reported, what the chart shows, and what is being said about it right now. It runs as a small Python script (scripts/news.py, needs yfinance) from the staskh/trading_skills repo, with timestamps in New York time. From the staskh/trading_skills repository (MIT). Honest caveats: coverage is limited to what Yahoo Finance aggregates, headlines can repeat across outlets or lag the events themselves, and the sentiment summary is a short qualitative read of those headlines, not a measured score; always open the source article before treating a headline as fact. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/news-sentiment
- Fiche en français: https://theskillharbor.com/fr/products/news-sentiment
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/news-sentiment/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
