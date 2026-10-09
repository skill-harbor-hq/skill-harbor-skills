<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-positions
description: "Read perp positions and margin, set leverage and margin mode, add isolated margin, check..."
---

# Hyperliquid Positions

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. The reads in this skill are safe, but its write actions (leverage changes, isolated margin adds, closes) act on a real account: on mainnet they move real margin and can change a position's liquidation price immediately. Curated by Skill Harbor: the positions and margin skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid. It starts from the concepts that decide whether a position survives: cross margin shares one pool across positions while isolated margin risks only its own; leverage is set per market and capped by margin tiers that shrink as notional grows; maintenance margin and liquidation are computed on the mark price, and the exchange's own liquidation price per position is the number to trust, never a recomputation. The reads pull positions, margin used, unrealised PnL, funding paid and liquidation distance from the account state, seconds before any action rather than from a stale brief. The writes are fenced to the desk's Execution Trader role on an approved ticket: setting leverage and margin mode before the entry it belongs to, adding isolated margin, and closing with an opposite reduce-only IOC sized from the live position. The clean-up teaching is unusually careful: after a full close, cancel the orphaned take-profit and stop orders; after a partial close, never sweep the stop that still protects the remainder, and replace a fixed-size stop at the...

- Listing: https://theskillharbor.com/products/hyperliquid-positions
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-positions
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-positions/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
