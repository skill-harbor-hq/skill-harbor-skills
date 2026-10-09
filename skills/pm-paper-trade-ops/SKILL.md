<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pm-paper-trade-ops
description: "Run, monitor, intervene in, and archive simulated prediction-market trading on oracle3. Simulation..."
---

# PM Paper Trade Ops

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill is a SIMULATION: paper trading uses no real money and places no real orders, and that is exactly its job; simulated fills are usually kinder than real ones, so good paper results are a filter, not a forecast of profit. Curated by Skill Harbor: the paper-trading runbook of oracle3, the open-source prediction-market engine for Polymarket, Kalshi, Solana and RSS event feeds. It starts a validated strategy in paper mode for a set duration, with an optional live monitor view, and runs the same control surface a live desk would use: status and state snapshots, pause and resume, hot-swapping the strategy mid-run, and stop. On any anomaly the rule is pause first, then decide. At the end, the run is archived properly: configuration, a state snapshot and the end-of-run summary go to a research folder, so every result can be replayed from its exact configuration (strategy reference, parameters, duration, venue). Two preconditions gate the start: the strategy passes validation, and at least one backtest or auto-tune result exists that a human can interpret. The skill's own hard rule is the safety core: never use live credentials during paper trading. From the YichengYang-Ethan/oracle3-prediction-market-agent repository (Apache-2.0). Honest caveats: a paper engine cannot reproduce a thin book fighting back, partial fills at the worst moment, or your own behaviour when real money moves...

- Listing: https://theskillharbor.com/products/pm-paper-trade-ops
- Fiche en français: https://theskillharbor.com/fr/products/pm-paper-trade-ops
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent/blob/main/skills/pm-paper-trade-ops/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
