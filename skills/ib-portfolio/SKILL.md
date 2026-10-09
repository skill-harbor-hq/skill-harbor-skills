<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ib-portfolio
description: "Your Interactive Brokers positions read straight from TWS or IB Gateway on your own machine..."
---

# IB Portfolio Positions

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Connected to the live port, this skill reads a real brokerage account holding real money. Curated by Skill Harbor: your own Interactive Brokers positions, read on your own machine. The skill connects to Trader Workstation or IB Gateway running locally with the API enabled and returns your current positions as structured JSON: symbol, quantity, average cost, market value, and unrealized profit and loss. It defaults to the paper-trading port (7497), accepts the live port (7496) or an IB_PORT environment variable, and if the configured port fails it retries the other one and remembers which account type answered. Once installed, asking what you own and what it is worth right now becomes a chat question instead of a platform session. It runs as a Python script (scripts/portfolio.py, needs the ib-async library) from the staskh/trading_skills repo. From the staskh/trading_skills repository (MIT). Honest caveats: know which account you are connected to before trusting the numbers (the automatic port fallback makes this worth double-checking, because paper and live balances look alike in a table); as documented, the skill fetches and reports positions and places no orders; your IB login stays inside TWS or Gateway on your machine, and account credentials never belong in a chat. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/ib-portfolio
- Fiche en français: https://theskillharbor.com/fr/products/ib-portfolio
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/staskh/trading_skills/blob/main/.claude/skills/ib-portfolio/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
