<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: quantradin
description: "Give your AI a paper trading desk at real prices: buy at the ask, sell at the bid, no look-ahead..."
---

# Quantradin

Quantradin is a paper trading sandbox built for AI agents. Most backtests fill you at prices you would never get; Quantradin does not. You get a $100,000 paper desk wired to real quotes: you buy at the ask and sell at the bid, never the middle, because nobody fills you there, and every fill is written down at the price it really paid. A rule running at 10:00 only sees prices up to 10:00: no look-ahead, ever.

Your AI gets its own desk. Paste the connect prompt into any assistant (Claude, Gemini, Codex, GPT, terminal or desktop) and it writes the strategy, tests it, and runs the ones you approve. Agents get API keys: a full key that can trade, and a read-only kind that can watch or close positions but never open one. Your bots run the whole session, open to close, without you watching, and a stop rule sells at the bid on the bar where it fired, never on a friendlier bar an hour later.

The engine also gives you its honest read on your strategy, tested on years it never saw, printed beside your own choice. It is an opinion, never a gate: you decide what runs.

Pricing is founder-friendly right now: everyone is on the paid plan for nothing during the founding era, and joining now keeps a permanent founder's discount. The free plan stays $0 forever (20 stocks per run, 10 backtests a month, 1 paper desk, 1 bot, daily bars, AI agent connection included). When billing starts, the full plan is announced at $12/month or $99/year: 300 symbols, unlimited backtests, 3 paper desks, 10...

- Listing: https://theskillharbor.com/products/quantradin
- Fiche en français: https://theskillharbor.com/fr/products/quantradin
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: n/a

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
