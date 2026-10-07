<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-search-first
description: "Research-before-coding workflow: search npm, PyPI, MCP servers, skills, and GitHub for existing..."
---

# Search-First

Curated by Skill Harbor: a workflow skill that systematizes the discipline of searching for existing solutions before writing code. It runs a five-stage pipeline: a tool-availability preflight (check which search channels actually work before relying on them), need analysis, parallel search across npm and PyPI, MCP servers, skills, and GitHub, candidate evaluation on functionality, maintenance, community, docs, license, and dependencies, and a decide step with four honest outcomes: adopt as-is, extend with a thin wrapper, compose small packages, or build custom but informed by research. A quick inline mode covers the mental checklist before writing any utility; a full agent mode handles non-trivial needs. Anti-patterns called out: jumping straight to code, ignoring MCP servers, silently skipping unavailable channels, over-customizing wrappers, and dependency bloat. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a workflow, nothing to install; its value depends on which search tools the agent can actually reach (npm, gh CLI, web search), and it reports skipped channels honestly rather than claiming coverage it does not have. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-search-first
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-search-first
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/search-first/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
