<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pm-live-trade-ops
description: "Run a validated oracle3 strategy with real money on Polymarket or Kalshi, behind explicit approval..."
---

# PM Live Trade Ops

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill runs LIVE trading: real orders, real money, real losses possible on every contract, and prediction-market positions can go to zero. Curated by Skill Harbor: the live-operations runbook of oracle3, the open-source prediction-market engine for Polymarket and Kalshi. It is deliberately gated: a live run may start only when the strategy passes validation, the latest backtest or auto-tune results are acceptable, recent paper runs behaved stably, and the user has explicitly approved going live. The start commands take venue credentials from your own environment (a wallet private key variable for Polymarket; an API key id and a private key file path for Kalshi), never from a chat. While the engine runs, you control it with status and state snapshots, pause, resume, and stop; the emergency order is written down and rehearsed in the skill: pause first, assess positions and open orders, engage the killswitch if needed, and only then stop. Every live run keeps a complete record (time, parameters, state snapshots, every intervention), and the MCP server has no live-trading tools at all, so live trading exists only through this CLI path. From the YichengYang-Ethan/oracle3-prediction-market-agent repository (Apache-2.0). Honest caveats: the gates protect you only if a human actually reads them, a killswitch reacts after a problem has started rather than preventing it, and credentials...

- Listing: https://theskillharbor.com/products/pm-live-trade-ops
- Fiche en français: https://theskillharbor.com/fr/products/pm-live-trade-ops
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent/blob/main/skills/pm-live-trade-ops/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
