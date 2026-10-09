<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pm-constraint-arbitrage
description: "Check whether related prediction-market contracts break a probability bound once venue fees are..."
---

# PM Constraint Arbitrage

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Most apparent arbitrage is a misread contract or a stale quote, the net edge after fees is often zero or negative, and a wrong assumption turns the trade into a directional bet that can lose money. Curated by Skill Harbor: the constraint-checking runbook of oracle3, the open-source prediction-market engine and MCP server for Polymarket and Kalshi. It answers questions like "does P(A) exceed P(B) even though A implies B?" by evaluating five relations between related contracts (implication, exclusivity, complement, same event on two venues, and event sum) against executable quotes and each venue's real fee schedule. The live check fetches quotes and fees, then reports the gross edge per contract, the fees per contract and the net edge per contract; only a positive net edge on a deep enough book earns a paper trade of each leg, at a limit no worse than the quoted ask. The skill's hard rules deserve quoting in spirit: never place real orders from it (the MCP server cannot, and the CLI live mode is out of scope here), always state the relation you assumed and why, report fees per leg, and remember that the check assumes every leg fills at the quoted price, which displayed sizes do not always allow. From the YichengYang-Ethan/oracle3-prediction-market-agent repository (Apache-2.0). Honest caveats: reading resolution rules is a judgment call about contract wording, and two markets that look...

- Listing: https://theskillharbor.com/products/pm-constraint-arbitrage
- Fiche en français: https://theskillharbor.com/fr/products/pm-constraint-arbitrage
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent/blob/main/skills/pm-constraint-arbitrage/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
