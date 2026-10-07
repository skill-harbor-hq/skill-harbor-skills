<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-context-budget
description: "Audit your Claude Code context window: inventory agents, skills, MCP servers, and rules by token..."
---

# Context Budget

Curated by Skill Harbor: a context budget skill that audits what your Claude Code context window is actually spending tokens on, so you can stop guessing why sessions feel sluggish. It inventories every component by estimated token cost: agents (flagging files over 200 lines and bloated frontmatter), skills (SKILL.md files over 400 lines, duplicate copies skipped), rules (files over 100 lines, overlap detection between rule files), and MCP servers (server and tool counts, roughly 500 tokens of schema overhead per tool, flagging servers with 20+ tools and servers that merely wrap simple CLI commands). The output is a prioritized list of token-savings recommendations, so you know exactly what to trim first for the most headroom. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure diagnostic guidance, nothing to install; token estimates are heuristics (words times 1.3), not metered billing; run it when sessions degrade or before adding new components, not obsessively. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-context-budget
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-context-budget
- Category: AI Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/context-budget/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
