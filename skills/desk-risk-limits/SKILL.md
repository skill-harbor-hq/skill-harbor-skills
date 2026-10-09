<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: desk-risk-limits
description: "Write your Hyperliquid desk's risk limits once, size every trade from its stop with stressed..."
---

# Desk Risk Limits (HyperGrok)

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Risk limits reduce how much a bad day can cost; they do not make a strategy profitable, and a gap through a stop can still exceed every number in the file. Curated by Skill Harbor: the risk-management skill of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid, and the gate every other desk skill answers to. It works in two halves. First, the limits themselves: an interview, one question at a time, writes a versioned limits file (network, account, maximum risk per trade and in total, leverage cap, maximum positions, allowed markets, mandatory exchange-resting stops, a daily loss stop, slippage tolerance, correlated-cluster limits, and standing approvals, which may only ever cover reduce-only protective stops, never entries). Hard desk ceilings sit above the file (2% of equity per trade, 6% total open risk, 20x leverage, a 10% daily loss stop): a limits file looser than a ceiling is not applied, and no agent may raise a ceiling. Second, sizing: every proposed trade is sized from its stop using a stressed distance that adds realistic slippage on the triggered stop plus both legs' taker fees, rounded down to the market's size decimals and checked against margin tiers, free margin with headroom, total open risk including reservations for pending tickets, and the daily loss stop; the worked example shows the naive calculation quietly overspending a 0.5% budget on every...

- Listing: https://theskillharbor.com/products/desk-risk-limits
- Fiche en français: https://theskillharbor.com/fr/products/desk-risk-limits
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/desk-risk-limits/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
