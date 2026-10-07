<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rohitg00-agentmemory-commit-context
description: "Trace a file, function, or line back to the agent session and commit that produced it — with strict..."
---

# Commit context — which agent session made this change?

Curated by Skill Harbor — a code-archaeology skill by @rohitg00 that answers "why is this code here" and "what was the agent doing when this changed" for agent-built codebases: find the SHA via `git blame` / `git log`, look it up through the AgentMemory tooling (`memory_commit_lookup`, `memory_recall`), and present the commit plus the linked session(s) with importance-filtered observations. Its defining feature is honesty under uncertainty — when a lookup returns `commit: null`, the skill reports "this commit predates session linking, so there is no recorded agent session" and never narrates intent from the diff alone. Includes a checklist (SHA comes from git, never guessed; session details quoted verbatim) and links to sibling skills (`commit-history`, `recall`). Honest caveats: it only works where the AgentMemory MCP/tools are actually installed and available to the agent; sessions must have been recorded — older commits return null by design, not by failure. Credit to its creator. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/rohitg00-agentmemory-commit-context
- Fiche en français: https://theskillharbor.com/fr/products/rohitg00-agentmemory-commit-context
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/rohitg00/agentmemory/blob/main/plugin/skills/commit-context/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
