<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-market-data
description: "Read live Hyperliquid prices, order book depth, funding, open interest, and candles with curl or..."
---

# Hyperliquid Market Data

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill only reads public market data and cannot place an order, but a price snapshot is not a signal: figures age in seconds, and acting on a stale or partial read can lose money fast. Curated by Skill Harbor: the read-only market data skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid. Everything is a keyless POST to the exchange's info endpoint, by curl or the official Python SDK: mid, mark and oracle prices, funding (an hourly rate, with history and cross-venue predictions that must be normalised by each venue's own funding interval before any comparison), open interest, 24h volume, margin tiers, spot metadata with its index naming, and the HIP-3 builder perp universes. The depth teaching is the heart of it: the order book endpoint returns a page of 20 levels, not the book, so the skill shows how to measure the page's reach in basis points, request coarser pages to see further, and quote any band beyond the reach as a floor rather than a total. Candles come with their real limit (only the most recent 5,000 per market and interval exist), and a dataset-saving pattern walks back to that ceiling for the strategy lab. Two desk scripts expose read-only snapshot contracts for the opening bell and a health check. Every reported figure carries its request type, network and UTC time, and reads default to mainnet even when the desk trades testnet, because testnet...

- Listing: https://theskillharbor.com/products/hyperliquid-market-data
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-market-data
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-market-data/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
