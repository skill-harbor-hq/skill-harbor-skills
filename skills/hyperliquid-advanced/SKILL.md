<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: hyperliquid-advanced
description: "The less common Hyperliquid actions and their rules: dead-man's switch, TWAP orders, spot orders..."
---

# Hyperliquid Advanced

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Most of this skill signs: TWAP orders, spot orders and the dead-man's switch act on a real account, and one of them can cancel every open order including the stop protecting a position. On mainnet that is real money with real loss possible. No action here promises a return. Curated by Skill Harbor: the advanced-actions skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid, where everything that signs is Execution Trader only, on an approved ticket. It covers the dead-man's switch (scheduleCancel, which cancels all of the account's open orders at a set time unless pushed out, capped at 10 triggers a day, and explicitly not position-aware: if it fires with a position open, that position is left unprotected and the skill says to declare it and run the incident playbook, not to treat re-arming as cleanup), TWAP orders (a size split into slices at fixed intervals, 30 seconds minimum, 5 minutes to 7 days in the docs with a 24-hour cap in the TypeScript schema, 100 USD minimum, each slice capped at 3 percent slippage, still one ticket stating size, minutes, randomisation and reduce-only), spot orders (asset id 10000 plus the pair index, price decimals from the base token, a 10 quote-token minimum, and Decimal-exact rounding helpers that verify the encoded size and price against the approved bound before signing), expiry and nonce rules (expiresAfter makes a late action...

- Listing: https://theskillharbor.com/products/hyperliquid-advanced
- Fiche en français: https://theskillharbor.com/fr/products/hyperliquid-advanced
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/hyperliquid-advanced/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
