<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pm-quant-strategy-authoring
description: "Turn a quantitative idea into tunable oracle3 QuantStrategy code: validate it, backtest it on..."
---

# PM Quant Strategy Authoring

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. A backtest describes the past of one market, auto-tuning can overfit that past beautifully, and neither promises that a strategy will make money live. Curated by Skill Harbor: the quantitative strategy-authoring runbook of oracle3, the open-source prediction-market engine and MCP server for Polymarket and Kalshi. Where the sibling agent skill is for LLM-driven decisions, this one is for numbers: it scaffolds a QuantStrategy subclass whose parameters live in the constructor as plain JSON-serializable values with meanings, bounds and defaults, precisely so the research auto-tune command can search them later. The workflow is strict about shape: strategy logic belongs in its own strategy file (never hard-coded into a command-line script), event handling stays limited to the event types the strategy actually needs, decisions are recorded, and runs are reproducible from the recorded file path, class name, parameters and command. Validation is a dry run, then a single-market backtest against a recorded history file, and only then preparation for tuning. The oldest rule in the book is stated as a hard rule: never use future information, no look-ahead. From the YichengYang-Ethan/oracle3-prediction-market-agent repository (Apache-2.0). Honest caveats: the more parameters a grid search tunes on the same history, the more the result describes that history instead of the market; treat tuned...

- Listing: https://theskillharbor.com/products/pm-quant-strategy-authoring
- Fiche en français: https://theskillharbor.com/fr/products/pm-quant-strategy-authoring
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent/blob/main/skills/pm-quant-strategy-authoring/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
