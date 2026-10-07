<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-token-budget-advisor
description: "Let the agent offer response-depth choices with token estimates before answering, at 25/50/75/100%."
---

# Token Budget Advisor

Curated by Skill Harbor: a behavior skill that teaches an agent to offer you a choice of response depth before answering. Instead of guessing how detailed you want an answer, the agent proposes four levels, 25%, 50%, 75%, 100%, each with a token estimate, and then answers at the level you pick. It uses simple calibration heuristics from the companion context-budget skill (prose at roughly words times 1.3, code-heavy text at roughly characters divided by 4) so the estimates stay honest without tooling. It knows when to stay quiet: if you already set a depth this session it maintains it silently, and it skips the offer entirely for answers that are trivially one line. It also knows that "token" sometimes means an auth or payment token, and stays out of the way then. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure behavior guidance, nothing to install, works in any chat including Muse; the estimates are heuristics, not metered billing, so treat them as relative sizes rather than exact counts. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-token-budget-advisor
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-token-budget-advisor
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/token-budget-advisor/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
