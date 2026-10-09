<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-trades-history
description: "Fetch your Interactive Brokers trade executions by account, date range or symbol, from the live API..."
---

# IB Trades History

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. This skill reads the execution history of a REAL Interactive Brokers account: the numbers describe what already happened, commissions and realized profit and loss included, they do not predict anything, there is a real risk of loss in any trading this history feeds into, and no output here is a promise of return. Curated by Skill Harbor: the IB trades history skill of staskh/trading_skills. Use it when you ask about your trades, executions or transaction history at Interactive Brokers, filtered by account, date range or symbol. It has three data sources and the skill is honest about each one: the live API, which in practice returns only the current TWS session despite what the API documentation implies (a weekend or prior-day lookback can return zero executions and look exactly like no trades), FlexReport through the Flex Web Service for full history, and local FlexReport XML files you exported yourself, which need no TWS or Gateway at all. The output is structured JSON: connection status, source used, the filters applied, an explicit data limitation warning on the live API path, the execution list, and per-symbol aggregates of bought, sold, commission and realized profit and loss. With the spread grouping option (FlexReport sources only, because only they carry the open and close indicator) raw fills are consolidated into legs and paired into vertical spreads with credit, width...

- Listing: https://theskillharbor.com/products/ib-trades-history
- Fiche en français: https://theskillharbor.com/fr/products/ib-trades-history
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-trades-history/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
