<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: position-sizer
description: "Risk-based position sizing for long stock trades: fixed-fractional, ATR-based, and Kelly criterion..."
---

# Position Sizer

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Correct position sizing limits how much a losing trade hurts; it does not make a trade profitable, and trading still involves real risk of loss. Curated by Skill Harbor: a focused calculator that answers "how many shares?" from a risk budget instead of a hunch. It supports three methods: fixed fractional (risk a set percentage of account equity per trade, 1% by default, using the distance from entry to stop), ATR-based sizing (the stop distance comes from the stock's Average True Range times a multiplier, so volatile names automatically get smaller positions), and the Kelly criterion (size from your historical win rate and average win/loss). Portfolio guardrails apply on top of every method: a maximum position size as a percentage of the account and a maximum sector exposure, with the final recommendation given as a full risk breakdown. Output defaults to whole shares; an optional fractional mode with configurable precision serves small accounts or high-priced stocks when the broker supports fractional shares. It runs on Python 3.9+ with the standard library only, and needs no API keys: you supply account size, entry, and stop (or ATR, or your win/loss statistics). From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: long stock trades only, no shorting, options, or futures sizing. The math assumes your stop actually executes near its price; gaps and slippage...

- Listing: https://theskillharbor.com/products/position-sizer
- Fiche en français: https://theskillharbor.com/fr/products/position-sizer
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/position-sizer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
