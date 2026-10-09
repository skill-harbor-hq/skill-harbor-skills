<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: priced-round-dilution
description: "Build the pre and post money ownership bridge for a simple priced equity round, with the simple..."
---

# Priced Round Dilution

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. A dilution bridge is arithmetic on stated terms, not legal or investment advice: the documents govern in any real financing, a founder or investor can still lose money on a correctly computed round, there is a real risk of loss, and no output here is a promise of return or of a completed financing. Curated by Skill Harbor: the priced round dilution skill at the root of andreworia/claude-finance-skills, a short and deliberately narrow skill. Use it when a founder wants to compare simple priced equity financing scenarios. It collects four inputs only, the pre-money equity value, the new cash, the fully diluted pre-round share count and any existing holder share count, and it applies the simple round mechanics exactly: post-money equals pre-money plus new cash, price per share equals pre-money divided by pre-round shares, and new investor ownership equals new cash divided by post-money. It then reconciles the new and existing share counts and checks that ownership sums to 100 percent. The skill points to its bundled dilution script for this exact simple case, and it is explicit about its boundary: if SAFEs, convertible notes, option pool top-ups, warrants, secondary shares or fees are present, the simple calculator stops and a term specific model must be built from the actual documents instead. It also insists on distinguishing cash going to the company from secondary proceeds, which old...

- Listing: https://theskillharbor.com/products/priced-round-dilution
- Fiche en français: https://theskillharbor.com/fr/products/priced-round-dilution
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/andreworia/claude-finance-skills/blob/main/skills/priced-round-dilution/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
