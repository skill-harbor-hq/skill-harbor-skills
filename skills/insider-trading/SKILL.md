<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: insider-trading
description: "Track insider buying and selling from public SEC Form 4 filings: who traded, their role, shares..."
---

# Insider Trading Tracker

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill tracks insider transactions from public data and regulatory filings (SEC Form 4 disclosures, surfaced through Yahoo Finance): it is a window on what company insiders have already declared in public, never a way to trade on non-public information, and never an encouragement of insider trading, which is illegal. Insiders also sell for many ordinary reasons (taxes, diversification, scheduled plans), and a declared purchase is a fact about the past, not a promise about the price: following it blindly carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: recent Form 4 activity for one ticker or a comma-separated list, over a trailing window you choose (90 days by default). It returns each transaction with the insider's name and role, the transaction type, shares, price, value, date and ownership type, plus a summary: net sentiment (net buying, net selling or neutral) with buy and sell counts and values; across several symbols, results are ranked by net buying value. Used well, it is context for your own research: an open-market purchase by an officer reads differently from an option exercise or a pre-scheduled sale, and the skill gives you the fields to tell them apart. It runs as a Python script (scripts/insider_trading.py, needs yfinance) from the staskh/trading_skills repo, with timestamps in New York time. From the staskh/trading_skills...

- Listing: https://theskillharbor.com/products/insider-trading
- Fiche en français: https://theskillharbor.com/fr/products/insider-trading
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/insider-trading/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
