<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: starchild-ai-agent-official-skills-coinglass
description: "Query crypto derivatives data — funding rates, open interest, liquidations, long/short ratios..."
---

# Coinglass: crypto derivatives data (funding, OI, liquidations, ETF flows)

💳 **Paid API required** — requires a CoinGlass API key; the skill's documented platform key runs on the Startup plan, and several endpoints (liquidation heatmap, individual liquidation orders, Hyperliquid position distribution, all-coin market summary) are 401-gated behind higher (Basic+) paid plans. Curated by Skill Harbor — a short pointer to @starchild-ai-agent's coinglass skill: a 37-tool script-mode skill for crypto derivatives data — funding rates, open interest (current and OHLC history), long/short ratios (global, top accounts, top positions), liquidations and liquidation history, taker volume and CVD, whale transfers and Hyperliquid whale alerts, plus BTC/ETH/SOL/XRP (US and Hong Kong) ETF flows — with a decision tree and keyword lookup for picking the right tool and interpretation guides (funding extremes, OI+price matrix, L/S crowding, CVD patterns, ETF flow reads). Honest caveats: **no license declared in the repository — license unknown**, so this is a short fiche linking to the source, without reusing its content; this is market data, not financial advice — verify everything against your own sources before trading; the skill is script-mode and forbids bash/file writes in normal operation. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/starchild-ai-agent-official-skills-coinglass
- Fiche en français: https://theskillharbor.com/fr/products/starchild-ai-agent-official-skills-coinglass
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/starchild-ai-agent/official-skills/blob/main/coinglass/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
