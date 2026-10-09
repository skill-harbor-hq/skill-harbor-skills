<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-find-short-roll
description: "Analyze roll options for existing short option positions, or find the best covered call or put to..."
---

# IB Short Roll Finder

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. This skill analyzes positions in a REAL Interactive Brokers account and proposes roll and covered call candidates: every candidate is a trade you would still have to place yourself and judge yourself, a roll can lock in a loss or add risk instead of reducing it, there is a real risk of loss on every short option position, and no output here is a promise of return. Curated by Skill Harbor: the IB short roll finder of staskh/trading_skills. Use it when you ask about rolling a short option position, finding roll candidates, writing covered calls, or managing option positions at Interactive Brokers. The skill auto-detects what you hold for the symbol and switches mode accordingly: with an existing short option position it analyzes roll candidates to other expirations and strikes (roll mode), with a long option position it finds the best short leg to complete a vertical spread (spread mode), and with long stock it finds the best covered call, or protective put, to open (new short mode); with none of these it returns an error unless you specify strike and expiry manually. The strike search band is IV-aware, scaled from the at-the-money implied volatility, the days to expiry of the nearest roll expiry and a multiplier you can raise for high-IV names, and the current position data includes IV and delta from IB model greeks. The output is a markdown report saved locally, leading with the...

- Listing: https://theskillharbor.com/products/ib-find-short-roll
- Fiche en français: https://theskillharbor.com/fr/products/ib-find-short-roll
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-find-short-roll/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
