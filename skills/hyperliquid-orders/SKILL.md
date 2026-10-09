<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-orders
description: "Place, cancel, and modify Hyperliquid orders correctly: rounding rules, client order ids, trigger..."
---

# Hyperliquid Orders

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill is a WRITE path: its snippets end in signed requests that place real orders, and on mainnet that is real money from the first fill, with losses possible on every position. Curated by Skill Harbor: the order-mechanics skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid, written in Python (official SDK) and TypeScript. It teaches the concepts traders get wrong: orders address an asset index, not a symbol; prices round to at most five significant figures with a decimals cap, sizes always round down; there is no market order, only an IOC limit bounded by a slippage tolerance; a client order id (cloid) on every order is what lets you reconcile when a response is lost; trigger orders fire on mark price and need a worst-acceptable price beyond the trigger (desk defaults: a 5% bound for stop-losses, 1% for take-profits); and entries can carry grouped take-profit and stop-loss children that live and die with the entry. Full worked code covers resting limits, market-style entries, grouped entries, stops on existing positions, cancels, and modifies (a stop can never be modified: place the new one, confirm it rests, then cancel the old, so the position is never naked). A complete error-string table maps exchange rejections to causes and fixes. The desk discipline around it is part of the skill: only the Execution Trader role sends, only on a ticket with a risk...

- Listing: https://theskillharbor.com/products/hyperliquid-orders
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-orders
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-orders/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
