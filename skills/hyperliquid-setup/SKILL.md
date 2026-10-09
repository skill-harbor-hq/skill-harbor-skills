<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-setup
description: "Prepare a computer to work with Hyperliquid: install the SDKs, default to testnet, check..."
---

# Hyperliquid Setup

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Setup is where a desk's worst mistakes are made: a main wallet key on a shared computer, or mainnet selected by accident, can cost real money before a single trade is placed. This skill is built to make both mistakes hard. No setup step promises a return. Curated by Skill Harbor: the setup procedure of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid. Its first three sections are read-only and safe at any time: the network table for mainnet and testnet (REST, WebSocket, app and the testnet faucet), the installs (Python 3.9 or newer with the official SDK pinned to a range, an optional TypeScript client needing Node 22.12 or newer, and curl with jq, which is enough for every read), and a no-key connectivity check that posts a price request to both networks and reports which one answered. Testnet is the default everywhere: nothing selects mainnet unless the network variable is set to mainnet on purpose, and the chosen network is recorded in the desk file. Section four, the API wallet, runs only when the user asks to move to a trading desk, and only after out-of-band approval coverage for the actual send paths is verified. The design is the lesson: the only key that ever reaches the desk computer is a trade-only API wallet the user creates and authorises in the Hyperliquid app, because it can trade and change leverage but cannot withdraw to Arbitrum, send tokens to...

- Listing: https://theskillharbor.com/products/hyperliquid-setup
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-setup
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
