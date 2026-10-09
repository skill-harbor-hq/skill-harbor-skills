<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-api-reference
description: "The compact desk reference for the Hyperliquid API: endpoints, every info request and exchange..."
---

# Hyperliquid API Reference

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This is a reference document, not a trading tool: it places no orders and needs no key, but the actions it catalogues include the signed exchange calls that move real money on mainnet, so treat it as a map of powerful machinery, not as an invitation. No entry here promises a return. Curated by Skill Harbor: the compact API reference of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid, stated as checked against the official documentation on 2026-08-16, with a pointer to fetch the live docs page whenever a field matters. It covers the endpoints and envelopes for mainnet and testnet (the unsigned info endpoint whose response is the bare payload, and the exchange endpoint whose signed body carries the action, nonce, signature and optional vault address and expiry), the full table of info request types with their parameters and return shapes (market metadata and contexts, book, candles with the 5,000-candle ceiling, funding history and cross-venue predicted fundings with the warning to normalise by each venue's own funding interval, account state, orders, fills, funding, ledger, portfolio, fees, rate limits, roles and sub-accounts), and the full table of exchange actions with each one's signing scheme and whether the desk uses it at all (orders, cancels, modifies and leverage updates yes; fund transfers, withdrawals, builder fees and staking marked no). It then gives the...

- Listing: https://theskillharbor.com/products/hyperliquid-api-reference
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-api-reference
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-api-reference/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
