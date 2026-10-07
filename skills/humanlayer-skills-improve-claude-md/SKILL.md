<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: humanlayer-skills-improve-claude-md
description: "Audit a CLAUDE.md, keep commands and foundational context bare, wrap domain guidance in..."
---

# Rewrite your CLAUDE.md with <important if> blocks so Claude actually obeys it

Curated by Skill Harbor — @humanlayer's skill for rewriting a CLAUDE.md so Claude Code actually follows it. The core insight: Claude Code injects a system reminder saying CLAUDE.md content "may or may not be relevant" to the task, so the model silently ignores parts it deems irrelevant — including the parts that matter. The fix is wrapping conditionally-relevant sections in `<important if="condition">` XML tags, exploiting the same XML pattern as Claude Code's own system prompt to give an explicit relevance signal. The workflow: keep foundational context bare (project identity, project map, tech stack — relevant to 90%+ of tasks), keep ALL commands in one `<important if>` block (foundational reference), then break every rule and domain section into narrowly-triggered blocks (imports, components, API routes, tests, state management), while deleting linter/formatter territory, anything discoverable from existing code, code snippets (replace with file-path references) and vague instructions. Includes a full before/after example of a bloated Express+React CLAUDE.md distilled into a lean conditional one. Honest caveats: methodology, not tooling — you need an existing CLAUDE.md to improve; the trick exploits an undocumented behavior of the system prompt, so it could weaken with future Claude Code updates. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/humanlayer-skills-improve-claude-md
- Fiche en français: https://theskillharbor.com/fr/products/humanlayer-skills-improve-claude-md
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/humanlayer/skills/blob/main/plugins/improve-claude-md/skills/improve-claude-md/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
