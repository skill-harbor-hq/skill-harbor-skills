<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-websocket
description: "Subscribe to live Hyperliquid data over WebSocket: mids, book, trades, candles, fills and order..."
---

# Hyperliquid WebSocket

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A live feed feels authoritative, but a silently dropped socket looks exactly like a quiet market; acting on data you believe is live when it is stale can lose money fast. This skill is read-only and cannot place an order, and no stream here promises a return. Curated by Skill Harbor: the WebSocket skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid, covering both networks' socket endpoints and the subscribe, unsubscribe, ping and pong protocol with its per-IP limits (10 connections, 1000 subscriptions, 2000 messages per minute, and a server that closes a connection silent for 60 seconds). The subscription table is the core reference: all mids, the order book with its push cadence, trades, candles that update in place until the bar closes, best bid and offer, per-market asset context, and the per-account streams (fills, order updates, account events, funding, per-market account data, account state and open orders, TWAP state, and the heavy frontend snapshot), plus the ability to post info requests over the socket itself. Working examples come in three forms: raw socket frames, the official Python SDK, and the TypeScript client which reconnects and resubscribes by default. The Python caveats are unusually honest and worth the listing on their own: the SDK manager pings for you but does not reconnect on a drop, several subscription types are acknowledged by the...

- Listing: https://theskillharbor.com/products/hyperliquid-websocket
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-websocket
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-websocket/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
