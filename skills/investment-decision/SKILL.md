<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: investment-decision
description: "A portable decision workflow that forces a sourced bear case, invalidation conditions and..."
---

# Investment Decision

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This is a decision support workflow: it connects to no broker, holds no credentials and places no order, and the human executes at their own broker, or not at all. Curated by Skill Harbor: the portable core of clawock, a Hong Kong and US stock desk whose author runs it on his own real book and publishes its decision ledger, losses included. The workflow runs inside your own agent: clawock first assembles a certified context (a request file with fingerprints), the agent researches with its normal tools and writes a decision artifact that must argue both sides, with a bull case and an opposing bear case that cite traceable evidence rather than assert conclusions. Thesis invalidation conditions are stated before any action is chosen, a high confidence decision must cite primary evidence, and if the action carries an order intent, the amounts are calculated arithmetically (quantity times price, converted at the stated FX rate) instead of being estimated in prose. Publication is gated: clawock refuses to publish a decision whose bear case is too thin, and the final receipt proves that one workflow version, one certified context and one artifact passed the deterministic checks. Afterwards, outcomes are scored in code against official market bars, and parameter changes can only be proposed, never self-applied: a named reviewer must accept the exact change, with rollback recorded. Honest...

- Listing: https://theskillharbor.com/products/investment-decision
- Fiche en français: https://theskillharbor.com/fr/products/investment-decision
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/KCNyu/clawock/blob/master/src/clawock/workflows/packs/investment-decision/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
