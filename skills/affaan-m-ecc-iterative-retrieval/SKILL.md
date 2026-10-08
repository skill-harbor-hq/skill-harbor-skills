<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-iterative-retrieval
description: "Fix the subagent context problem with Muse: a dispatch-evaluate-refine-loop that progressively..."
---

# Iterative Retrieval Pattern

Curated by Skill Harbor: a retrieval pattern that makes Muse solve the subagent context problem instead of guessing what a subagent needs upfront. The problem is real: subagents do not know which files contain the relevant code or what terminology the project uses, so sending everything blows the context limit and sending nothing leaves them blind. The solution is a four-phase loop, dispatch, evaluate, refine, loop, capped at three cycles: start with a broad keyword query, score each retrieved file on a 0 to 1 relevance scale with the reason and the missing context noted, refine the query by adding discovered patterns and terminology while excluding confirmed irrelevant paths, and repeat until three or more high-relevance files are found or the cap is hit. Worked examples show a bug-fix context retrieval and a feature-implementation retrieval where the second cycle discovers the codebase says throttle instead of rate limit. An agent-prompt snippet shows how to embed the pattern in instructions, and the best practices close with the line that matters: start broad and narrow progressively, learn the codebase terminology from the first cycle, and stop at good enough because three high-relevance files beat ten mediocre ones. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the relevance scoring is heuristic, tune it to your retrieval backend; the three-cycle cap is a starting default, not a law; it optimizes retrieval...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-iterative-retrieval
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-iterative-retrieval
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/iterative-retrieval/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
