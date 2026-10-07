<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: anthropics-claude-code-mcp-integration
description: "Wire Model Context Protocol servers into Claude Code plugins — stdio, SSE, HTTP and WebSocket..."
---

# MCP integration for Claude Code plugins

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): Anthropic's official MCP-integration skill from the claude-code plugin-dev plugin — the complete guide to connecting Model Context Protocol servers to Claude Code plugins. Covers the two config methods (dedicated `.mcp.json` at the plugin root vs inline `mcpServers` in plugin.json), the four server types (stdio for local tools, SSE for hosted OAuth services, HTTP for token-auth REST APIs, WebSocket for real-time), environment variable expansion (`${CLAUDE_PLUGIN_ROOT}` for portability, user env vars for secrets), MCP tool naming (`mcp__plugin_<plugin>_<server>__<tool>`) and how to pre-allow them in command frontmatter, lifecycle management, authentication patterns (automatic OAuth, header tokens, stdio env vars), integration patterns (simple tool wrapper, autonomous agent, multi-server plugin), security best practices (HTTPS only, env vars for tokens, specific tools pre-allowed — never wildcards), error handling, performance, local testing with `/mcp` and `claude --debug`, and an implementation workflow. Honest caveats: guidance only — the agent must already run Claude Code; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/anthropics-claude-code-mcp-integration
- Fiche en français: https://theskillharbor.com/fr/products/anthropics-claude-code-mcp-integration
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/anthropics/claude-code/blob/main/plugins/plugin-dev/skills/mcp-integration/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
