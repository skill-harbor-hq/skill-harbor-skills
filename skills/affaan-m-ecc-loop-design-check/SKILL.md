<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-loop-design-check
description: "Design goal-oriented agent loops that will not run away: machine-decidable goals, plan/build/judge..."
---

# Loop Design Check

Curated by Skill Harbor: the design half of agent loops, the part that decides whether the loop deserves to exist and will not sprint toward a goal nobody questioned. The premise: an LLM is feed-forward, prompt in and tokens out, with no built-in steering across turns; wrapping a feedback loop around it makes it behave like a goal-oriented system, but only if the goal is right. The skill draws the red line between two feedback levels: execution feedback (how far from the literal goal, owned by the machine) and judgment feedback (is this goal itself right, should it change, should it stop, always owned by the human). Handing judgment to the machine removes the high-level feedback and the loop sprints, fast and hard, toward a goal no one questioned. Action 1 writes a loop in five steps, starting with subtraction: four conditions for whether you should build it at all. Action 2 reviews an existing loop for the failure modes: spinning, Goodhart-gaming the verifier, running a wrong answer to completion. Plan/build/judge skeletons and runaway prevention are covered; the mechanism layer (pipelines, DAGs, long-run recovery) is explicitly left to autonomous-loops. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this covers goal design and runaway checks only, not loop wiring; a one-off task should not get a loop at all. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-loop-design-check
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-loop-design-check
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/loop-design-check/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
