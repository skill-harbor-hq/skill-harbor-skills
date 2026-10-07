<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: anthropics-claude-code-command-development
description: "Build custom slash commands — YAML frontmatter, arguments, file references, bash execution..."
---

# Command development for Claude Code — build reusable slash commands

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): Anthropic's official command-development skill from the claude-code plugin-dev plugin — the complete guide to building slash commands. Covers the core principle (commands are instructions FOR Claude, not messages to the user), command locations (project `.claude/commands/`, personal `~/.claude/commands/`, plugin), the YAML frontmatter fields (`description`, `allowed-tools`, `model`, `argument-hint`, `disable-model-invocation`), dynamic arguments (`$ARGUMENTS`, `$1`/`$2`), file references with `@` syntax, inline bash execution for gathering context, flat vs namespaced organization, best practices (single responsibility, argument validation, scoped tools), common patterns (review, testing, documentation, PR workflow), troubleshooting, and plugin-specific features (`${CLAUDE_PLUGIN_ROOT}`, command/agent/skill/hook integration, validation patterns). Honest caveats: guidance only — the agent must already run Claude Code; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/anthropics-claude-code-command-development
- Fiche en français: https://theskillharbor.com/fr/products/anthropics-claude-code-command-development
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/anthropics/claude-code/blob/main/plugins/plugin-dev/skills/command-development/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
