<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-account
description: "Read a Hyperliquid account with only its public address: positions and margin, spot balances, open..."
---

# Hyperliquid Account

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. These reads expose the full state of a real trading account, including liquidation prices and funding paid; the address is public, but what you do with a live read can still lose money, and a stale snapshot read as current is a classic way to size a trade wrong. No read here promises a return. Curated by Skill Harbor: the account-reading skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid. Every read is an unsigned POST to the info endpoint, by curl or the Python SDK, and needs only the account address, which must be the main wallet the desk trades for, never the API wallet's address (queries on an agent address return empty results that look like an empty account). The perp state read returns positions with signed size, entry, mark-driven liquidation price, margin used, leverage and cumulative funding, plus account value, total notional and withdrawable; a dedicated section warns against assuming the separate spot and perp balance model, because unified, portfolio-margin and DEX-abstraction account modes change what equity and free margin even mean, and an unverifiable mode must be reported as unavailable rather than guessed. Around it: spot balances with amounts held in open orders, open orders in two forms (the plain list, and the frontend form that actually shows trigger details, reduce-only flags and position take-profit and stop-loss links), order status...

- Listing: https://theskillharbor.com/products/hyperliquid-account
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-account
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-account/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
