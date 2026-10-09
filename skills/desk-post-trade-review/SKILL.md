<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: desk-post-trade-review
description: "Journal every desk day and review each closed trade from the exchange record: process graded apart..."
---

# Desk Post-Trade Review

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A review explains what a finished trade cost and how it was run; it cannot make the next trade profitable, and a good outcome on a broken process is luck, not evidence. No review here is a promise of return. Curated by Skill Harbor: the journaling and review procedure of HyperGrok, Galleon Labs' seven-agent trading desk for Hyperliquid, written for the Trade Reviewer role. It has four parts. First, the journal: one append-only file per active day, every line with a UTC time and an id, entries for openings, risk decisions, approvals, sends, fills, closes, limit changes, incidents and notes, with corrections added as new lines and no opinions allowed. Second, the trade review, triggered when a proposal closes: it works from the exchange record first (the proposal file, fills for the window, historical orders and order status by cloid, funding paid), and computes entry and exit slippage in basis points, fees in dollars and as a share of notional with maker and taker noted, funding over the holding window, the net result in dollars and in R, whether a reduce-only stop rested on the exchange for the entire life of the position, lifecycle completeness, and holding time. The grade keeps two columns strictly apart: process (clean, minor break or major break, with the stage named; any send without a PASS or an approval by id, any missing protection, any resend on an unknown result or any...

- Listing: https://theskillharbor.com/products/desk-post-trade-review
- Fiche en français: https://theskillharbor.com/fr/products/desk-post-trade-review
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/galleonlabs/hypergrok-trading-desk/blob/main/skills/desk-post-trade-review/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
