<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earnings-calendar
description: "Upcoming earnings dates for one ticker or a whole watchlist, sorted by date, with before or after..."
---

# Earnings Calendar

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. An earnings date is a risk marker, not a signal: stocks gap on results in both directions, options premiums inflate into the print and collapse after it, and trading around earnings carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: the next earnings date for one ticker or a comma-separated list, pulled from Yahoo Finance. For each symbol it returns the next earnings date, the timing (BMO, before market open, or AMC, after market close, when known) and the consensus EPS estimate when one is available; for several symbols the results come back sorted by date, soonest first, which turns a watchlist or a portfolio into a simple forward calendar of event risk. It is the planning companion to the rest of this options toolkit: check which of your positions report soon, see the estimate the print will be judged against, and decide your hedging or sizing before the date arrives rather than after. It runs as a Python script (scripts/earnings.py, needs pandas and yfinance) from the staskh/trading_skills repo, with timestamps in New York time and a data delay field stamped on the output. From the staskh/trading_skills repository (MIT). Honest caveats: Yahoo Finance dates and estimates are unofficial and can shift, since companies move report dates and estimates get revised, so confirm a date you would act on against the company's own investor relations...

- Listing: https://theskillharbor.com/products/earnings-calendar
- Fiche en français: https://theskillharbor.com/fr/products/earnings-calendar
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/earnings-calendar/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
