<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: trailofbits-skills-chrome-mcp-troubleshooting
description: "Diagnose the Claude.app-vs-Claude-Code native-host conflict and run the reset procedures —..."
---

# Fix Claude in Chrome MCP connectivity issues

Curated by Skill Harbor — the chrome-mcp-troubleshooting skill curated by @trailofbits (original skill by @jeffzwang): use when the Claude in Chrome MCP tools fail with "Browser extension is not connected" or behave erratically. It documents the primary conflict — Claude.app (Cowork) and Claude Code CLI register competing native-messaging hosts with incompatible socket formats — and gives the fix: disable the native-messaging config for whichever one you're NOT using (you can't run both), a chrome-mcp-toggle shell snippet for your ~/.zshrc, a full reset procedure (disable config, rewrite the version wrapper dynamically, kill the native host, clear sockets, restart Chrome, verify the right binary and socket, restart Claude Code), quick-diagnosis commands (which binary, where the socket is, what's connected, which configs are active), and fixes for the other common causes (extension in multiple Chrome profiles, multiple Claude Code sessions, hardcoded version in the wrapper, TMPDIR not set). Honest caveats: macOS only — paths and tools (~/Library/Application Support/, osascript) don't apply to Linux or Windows; the skill runs diagnostic shell commands (ps, lsof, mv on your own Chrome config files, pkill chrome-native-host) that act only on your own local machine — read them before running; not for general Chrome automation issues or network problems. CC-BY-SA-4.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/trailofbits-skills-chrome-mcp-troubleshooting
- Fiche en français: https://theskillharbor.com/fr/products/trailofbits-skills-chrome-mcp-troubleshooting
- Category: Browser Automation
- Price: Free
- Verification: unverified
- Source repo: https://github.com/trailofbits/skills/blob/main/plugins/claude-in-chrome-troubleshooting/skills/chrome-mcp-troubleshooting/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
