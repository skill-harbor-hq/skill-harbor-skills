<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: desk-execution-protocol
description: "The Execution Trader's discipline for turning an approved ticket into exactly one Hyperliquid..."
---

# Desk Execution Protocol

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This is the one desk skill that ends in a signed request to the exchange: on mainnet every send is real money, leveraged positions can be liquidated, and a mishandled resend can double a position. No procedure here promises a return. Curated by Skill Harbor: the execution discipline of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid. The API mechanics live in the sibling orders and positions skills; this skill is the procedure around them. It starts from an approved proposal file carrying a Risk Manager PASS and exact ticket fields, plus the user's approval by id inside the ticket's expiry, and runs an eight-point pre-send checklist before anything is sent: ticket integrity (any economic change means a new ticket id, a new PASS and a new approval), network and account matching the ticket, the API wallet verified as an approved agent for that account, a fresh price still inside the slippage tolerance, correct rounding and minimum notional, a fresh cloid with the signed nonce and an expiresAfter deadline recorded, one action per send with entry, stop and take-profit grouped, and capacity re-read with no unreconciled send outstanding. The send itself happens exactly once, with a finite timeout and the raw response captured. A timeout or a lost response is an unknown result, treated as possibly executed: never resend, reconcile by cloid through order status, open orders...

- Listing: https://theskillharbor.com/products/desk-execution-protocol
- Fiche en français: https://theskillharbor.com/fr/products/desk-execution-protocol
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/desk-execution-protocol/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
