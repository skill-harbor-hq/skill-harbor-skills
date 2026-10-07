<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: franalgaba-grimoire-grimoire-polymarket
description: "Query Polymarket market data and CLOB state, and manage CLOB orders through the grimoire venue..."
---

# Polymarket market data and CLOB orders via the Grimoire venue CLI

⚠️ GAMBLING / PREDICTION MARKETS — Polymarket is real-money betting on event outcomes: check your local laws before use (prediction-market betting is restricted or illegal in some jurisdictions). This is NOT financial advice — Skill Harbor lists the tool, never an endorsement of any trade. 💳 Real money required: order placement needs a funded Polygon (chain 137) wallet and POLYMARKET_PRIVATE_KEY. Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @franalgaba's venue adapter exposes Polymarket market discovery and CLOB data through the `grimoire venue polymarket` CLI — `search-markets` (by query, slug, event, tag, category, league, sport, with open/active/tradable filters), the official passthrough groups `markets` (list/get/search/tags) and `data` (positions, trades, leaderboards), plus legacy aliases (`book`, `midpoint`, `spread`, `price`, `price-history`, `open-orders`). The wrapper intentionally BLOCKS the `wallet`, `bridge`, `approve`, `ctf`, `setup`, `upgrade` and `shell` groups — but order placement IS exposed: spell actions support `order` / `cancel_order` / `cancel_orders` / `cancel_all` (custom op, token_id/price/size/side/order_type, GTC-GTD limit routing and FOK-FAK market routing, `mid_price` metric for spell comparisons). Honest caveats: the agent CAN place real orders — never let it trade unsupervised, double-check every order's token, price, size and side; keep your private key in the secure vault, never pasted...

- Listing: https://theskillharbor.com/products/franalgaba-grimoire-grimoire-polymarket
- Fiche en français: https://theskillharbor.com/fr/products/franalgaba-grimoire-grimoire-polymarket
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/franalgaba/grimoire/blob/main/skills/grimoire-polymarket/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
