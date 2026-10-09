<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-option-chain
description: "The option chain from your own Interactive Brokers account: equities, ETFs and futures options with..."
---

# IB Option Chain

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Connected to the live port, this skill reads quotes against a real brokerage account, and a live chain invites live trades: option prices move fast, futures options add their own margin and expiry rules, and trading on any of it carries a real risk of loss. No output here is a promise of return. Curated by Skill Harbor: the option chain for one symbol and one expiration, fetched from Interactive Brokers itself instead of a free web source. It covers equities and ETFs and also futures options (FOP), the coverage free sources handle badly: the asset type is resolved from IB contract details with no hardcoded symbol table, trying a SMART stock first and falling back to a future when no stock exists, so NQ, GC and RTY resolve as futures while AAPL resolves as a stock; roots that are both a stock and a futures root (ES is Eversource, CL is Colgate) default to the equity, with a flag to force the future. Each call and put comes back with strike, bid, ask, last price, volume, open interest, implied volatility, the IB model greeks (delta, gamma, theta, vega) and, for futures, the contract multiplier, next to the underlying price; you list the available expirations first, then fetch one expiry, and the agent presents the chain as a table with high-volume strikes and notable IV levels highlighted. It runs as a Python script (scripts/options.py, needs the ib-async library) from the...

- Listing: https://theskillharbor.com/products/ib-option-chain
- Fiche en français: https://theskillharbor.com/fr/products/ib-option-chain
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-option-chain/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
