<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: portfolio-manager
description: "Analyze a live Alpaca brokerage portfolio through the Alpaca MCP server: allocation..."
---

# Portfolio Manager

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill reads a real brokerage account; rebalancing suggestions are analysis, not instructions to trade, and investing involves real risk of loss. Curated by Skill Harbor: a portfolio review workflow that works from your actual holdings instead of hand-typed numbers. It connects to the Alpaca MCP Server to pull account equity, buying power and cash, every current position with quantity, cost basis and market value, and portfolio history, then analyzes asset allocation, diversification and sector concentration, risk metrics, and each individual position, and finishes with rebalancing recommendations in a detailed report. If the MCP server is not connected, the skill walks you through setup using its included reference (references/alpaca-mcp-setup.md), and a REST fallback exists for environments where MCP tools are unavailable: a connection-check script verifies the account and positions endpoints and prints a redacted diagnostic, placing no orders and writing no report. From the tradermonty/claude-trading-skills repository (MIT). Honest caveats: an Alpaca brokerage account is required, and the credentials (ALPACA_API_KEY and ALPACA_SECRET_KEY) belong in environment variables, never pasted into a chat, a report, or a commit; start with a paper-trading account (ALPACA_PAPER=true) until you trust the setup. Analysis is only as current as the Alpaca data feed, and the skill analyzes and...

- Listing: https://theskillharbor.com/products/portfolio-manager
- Fiche en français: https://theskillharbor.com/fr/products/portfolio-manager
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/portfolio-manager/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
