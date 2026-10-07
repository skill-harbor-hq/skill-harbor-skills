<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: dboeckli-ai-agent-skills-cc-best-practices
description: "Use Claude Code effectively — give Claude a runnable way to verify its work, use the Explore → Plan..."
---

# Claude Code best practices: verify, explore-plan-implement, manage context

Curated by Skill Harbor — @dboeckli's Claude Code best-practice guide (built from Anthropic's official best-practices documentation): the single governing constraint is that Claude's context window fills up fast and performance degrades as it fills — everything flows from that. Step 1, always give Claude a runnable way to verify its work (test suite, build exit code, linter, diff script) and ask for evidence, not assertions. Step 2, use the Explore → Plan → Implement workflow for non-trivial tasks — enter plan mode, let Claude read the codebase, draft the plan, then implement. Step 3, write specific, scoped prompts (@filename, symptoms not guesses, existing patterns). Step 4, keep CLAUDE.md short and actionable — include only what Claude cannot infer ("would removing this cause mistakes?"). Step 5, manage context aggressively (/clear between tasks, /compact with a hint, /rewind, /btw; after two failed corrections, clear and write a better prompt). Step 6, use subagents for investigation and review in a fresh context. Plus non-interactive mode, fan-out loops, parallel sessions with git worktrees, and a common failure patterns reference. Honest caveats: methodology only — you need Claude Code installed to apply it; the full CLI command reference lives in the repo's references/commands.md. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/dboeckli-ai-agent-skills-cc-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/dboeckli-ai-agent-skills-cc-best-practices
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/dboeckli/ai-agent-skills/blob/master/.claude/skills/cc-best-practices/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
