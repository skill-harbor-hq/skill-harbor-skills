<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: tabbit-browser-tabbit-devtools-skill-tabbit-devtools
description: "⚠️ AUTHORIZED USE ONLY — connect agent-browser to the Tabbit browser: read the DevToolsActivePort..."
---

# Tabbit DevTools — drive the Tabbit browser via CDP through agent-browser

Curated by Skill Harbor — ⚠️ AUTHORIZED USE ONLY: this skill gives your agent full control of a LIVE browser — open tabs and logged-in sessions are visible and actionable, so use it only for your own accounts and systems, never against third parties or accounts you do not own. @tabbit-browser's tabbit-devtools skill: a connection recipe for driving the Tabbit browser (a Chromium-based browser) from an agent through the agent-browser CLI over the Chrome DevTools Protocol. The agent reads Tabbit's live DevToolsActivePort file (platform-specific paths for macOS and Windows), builds the full browser WebSocket endpoint (ws://127.0.0.1:<port><path> — preferred over the raw port because Tabbit's HTTP discovery routes may 404), hands off to agent-browser --cdp via the bundled wrapper scripts (run_agent_browser_on_tabbit.py for actions, discover_tabbit_cdp.py for structured connection facts), and then works with the normal agent-browser vocabulary (open, snapshot, click, fill, press). It states its constraints clearly: it solves the connection problem only — no parallel automation layer, no custom CDP client, no daemon, no promise that chrome-devtools MCP can take over Tabbit; if agent-browser is unavailable it stops at connection guidance. Honest caveats: this connects the agent to your LIVE browser — open tabs and logged-in sessions are visible, so grant access deliberately (anonymous-profile guidance is referenced); you need the agent-browser CLI in the environment...

- Listing: https://theskillharbor.com/products/tabbit-browser-tabbit-devtools-skill-tabbit-devtools
- Fiche en français: https://theskillharbor.com/fr/products/tabbit-browser-tabbit-devtools-skill-tabbit-devtools
- Category: Dev
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tabbit-browser/tabbit-devtools-skill/blob/main/skills/tabbit-devtools/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
