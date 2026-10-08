<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-team-builder
description: "Interactive picker that discovers your agent personas, groups them by domain, dispatches up to five..."
---

# Team Builder

Curated by Skill Harbor: an interactive menu for browsing and composing agent teams on demand, from a community contributor, listed here with credit to its creator. Agent files must be markdown files containing a persona prompt (identity, rules, workflow, deliverables); the first heading is used as the agent name and the first paragraph as the description. Agents are discovered two ways, merged and deduplicated by name: the `claude agents` command (primary, covers user agents, plugin agents and built-ins automatically, including ECC marketplace installs) and file globs over `./agents/**/*.md` and `~/.claude/agents/**/*.md` (fallback, for reading agent content). Earlier sources take precedence on name collisions: user agents, then plugin agents, then built-ins. Both flat and subdirectory layouts are supported; the domain is inferred from the folder name, or from shared filename prefixes in flat layouts. You pick up to five personas, they are dispatched in parallel on one task, and their outputs are synthesized into a unified report of agreements and conflicts. From the affaan-m/ECC repository (MIT). Honest caveats: community skill; every dispatched agent is a full session, so five parallel agents cost five sessions of tokens; in flat layouts the domain algorithm splits at the first hyphen, so multi-word domains need the subdirectory layout. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-team-builder
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-team-builder
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/team-builder/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
