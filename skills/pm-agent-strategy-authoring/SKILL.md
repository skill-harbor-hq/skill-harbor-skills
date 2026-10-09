<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pm-agent-strategy-authoring
description: "Turn an LLM-driven idea into runnable oracle3 AgentStrategy code, then judge it the only honest..."
---

# PM Agent Strategy Authoring

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. Prediction-market contracts can go to zero, a strategy that behaved in simulation can lose real money, and no backtest or paper run promises a return. Curated by Skill Harbor: the strategy-authoring runbook of oracle3, an open-source prediction-market trading engine and MCP server for Polymarket, Kalshi and other venues (pip install oracle3). This skill covers the LLM-driven flavour: it scaffolds an AgentStrategy subclass with the strategy create command, has the model or an external API make decisions inside process_event, and requires the reasoning to be written down on every decision with record_decision so the run can be monitored and reviewed afterwards. The discipline is explicit: check the control plane's pause flag before every decision, give every external call a timeout so it can never block the event loop, record the strategy file, class name and command for reproducibility, and never use future information. Validation is a short dry run on a handful of events; evaluation is paper trading with the monitor on, because agent strategies cannot be grid-searched or auto-tuned, a limit the skill states plainly. Mid-run you can pause, resume, and even hot-swap the strategy file. From the YichengYang-Ethan/oracle3-prediction-market-agent repository (Apache-2.0). Honest caveats: an LLM-driven strategy is non-deterministic by design, so identical code can decide differently tomorrow...

- Listing: https://theskillharbor.com/products/pm-agent-strategy-authoring
- Fiche en français: https://theskillharbor.com/fr/products/pm-agent-strategy-authoring
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent/blob/main/skills/pm-agent-strategy-authoring/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
