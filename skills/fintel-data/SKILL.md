<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: fintel-data
description: "Fintel institutional data by API or MCP: short interest, borrow rates, fails-to-deliver, 13F..."
---

# Fintel Data

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Short interest, borrow costs and insider activity are facts about positioning, not predictions: a heavily shorted stock can keep falling, a squeeze setup can fail, and trading on any of it carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: a read-only bridge to Fintel (fintel.io), an institutional market intelligence platform whose strongest datasets are the ones most providers lack. Through the REST API, or the official MCP server backed by the same data contract, it covers short interest and days to cover, borrow rate and shares available to borrow, daily short volume, SEC fails-to-deliver records, 13F institutional owners, insider buying and selling from SEC Form 3, 4 and 5 filings, analyst price targets and ratings, revenue and EPS forecasts, end-of-day and last prices, dividend and earnings history and calendars, leaderboards, and the user's own watchlists and alerts. Securities resolve by ticker, company name, CUSIP, ISIN or FIGI, and answers are formatted with context (short interest as a share of float, days to cover, borrow fee direction) rather than raw numbers alone. From the himself65/finance-skills repository (MIT). Honest caveats: both surfaces need a Fintel API key from a Fintel API plan, kept in the FINTEL_API_KEY environment variable or a local .env file, never in the chat; some datasets, short interest in particular, must be...

- Listing: https://theskillharbor.com/products/fintel-data
- Fiche en français: https://theskillharbor.com/fr/products/fintel-data
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/data-providers/skills/fintel-data/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
