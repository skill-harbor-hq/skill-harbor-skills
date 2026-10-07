<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: onewave-ai-cash-flow-forecaster
description: "A 13-week cash forecast that circles the crunch weeks before they hit."
---

# Cash Flow Forecaster Skill for Muse

A rolling 13-week cash-flow forecast for small businesses — the report that tells you whether you survive the quarter. It reconstructs 8–12 weeks of history from your bank exports to learn the rhythm (payroll cadence, rent day, weekly spend, deposit patterns), schedules the knowns (AR placed in the week each invoice is *likely* paid — using each customer's historical lateness, not the printed due date; payroll, rent, loans, insurance, quarterly estimated taxes), models variable spend as labeled estimates, then flags every week ending below your comfort level as CRUNCH — with concrete levers per crunch week: which AR to chase now, which AP can slide two weeks, where the credit line covers, what pausing owner draws buys. Strict rules: payment behavior beats due dates, never invent inflows, estimates stay labeled and totaled separately, weekly (not monthly) granularity, re-run weekly against actuals. Output: cash-flow-13wk.csv plus a summary. Discovered via skills.sh. Honest note: garbage in, garbage out — it needs real bank exports, AR aging, and bill schedules to work; examples assume US-style payroll and quarterly estimated taxes, so adapt timing to your jurisdiction. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/onewave-ai-cash-flow-forecaster
- Fiche en français: https://theskillharbor.com/fr/products/onewave-ai-cash-flow-forecaster
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/onewave-ai/claude-skills/blob/main/cash-flow-forecaster/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
