<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-pmcc-advisor
description: "A Poor Man's Covered Call checkup on your Interactive Brokers portfolio: short-leg assignment risk..."
---

# IB PMCC Advisor

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This advisor analyzes positions in a real brokerage account; a roll it suggests moves real money when you act on it. Curated by Skill Harbor: a dedicated checkup for Poor Man's Covered Call positions (a long LEAPS call financed by a short near-term call) held at Interactive Brokers. The advisor scans your IB portfolio, identifies each diagonal spread, and for every short leg reports delta, implied volatility, and a model assignment probability, then projects daily profit and loss out to the short expiry, flags the dangerous ones (assignment probability above 40 percent, fewer than 7 days to expiry, earnings landing inside the short window), and ranks the top three roll candidates under strict rules (delta at or under 0.40, net credit no worse than a small debit), ending in a side-by-side comparison and a hold, roll, or close recommendation. The default answer is a concise inline summary, with a full markdown report only when you ask for one. It runs as a Python script from the staskh/trading_skills repo against TWS or IB Gateway on your machine. From the staskh/trading_skills repository (MIT). Honest caveats: start on the paper account before trusting it near live positions; the assignment probability is a Black-Scholes model estimate (N(d2)), not a guarantee, and early assignment around dividends or deep in-the-money shorts can ignore it; roll candidates are analysis, and as...

- Listing: https://theskillharbor.com/products/ib-pmcc-advisor
- Fiche en français: https://theskillharbor.com/fr/products/ib-pmcc-advisor
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-pmcc-advisor/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
