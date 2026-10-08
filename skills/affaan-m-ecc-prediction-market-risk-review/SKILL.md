<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-prediction-market-risk-review
description: "Pre-flight risk review for prediction-market workflows: advice boundaries, venue rules, data..."
---

# Prediction Market Risk Review

Curated by Skill Harbor: a review gate to run before any prediction-market workflow touches user financial context, venue authentication, portfolio data, automation, or execution-capable tools. Checks five gates. Advice boundary: confirm the output is informational, strip buy/sell/hold/size recommendations, keep manual user decision points explicit. Venue and regulatory boundary: identify venue terms, geography restrictions, account limits, and API rules, and flag betting, derivatives, securities, or commodities ambiguity for legal review. Data quality: check liquidity, spread, resolution rules, stale prices, and source timestamps, and never mix public and private sources without labels. Security: never request or store private keys, seed phrases, or passwords; keep API keys out of logs and docs; read-only scopes by default; require circuit breakers, spend limits, dry runs, and human approval before any execution. Privacy: minimize user portfolio and financial data, redact private sources in public artifacts. Returns scope reviewed, pass/warn/fail findings, blocked actions, required mitigations, and a safe next step. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a review gate, not legal advice and not a compliance certification. Venue terms change; verify them at the source before acting. If any execution-capable step is requested, a separate implementation plan and explicit user approval are required. Skill...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-prediction-market-risk-review
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-prediction-market-risk-review
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/prediction-market-risk-review/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
