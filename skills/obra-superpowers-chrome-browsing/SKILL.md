<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: obra-superpowers-chrome-browsing
description: "One action-based MCP tool covering navigate/click/type/extract/eval, multi-tab management, dialog..."
---

# Direct Chrome control through the use_browser MCP tool: tabs, forms, content extraction

Curated by Skill Harbor — @obra's browsing skill: full control of a real Chrome through a single `use_browser` MCP tool — navigate and wait (elements, text), click/type/select/keyboard interactions, CDP-level mouse (hover, drag-drop, move, scroll) that bypasses synthetic-event detection, file uploads, extraction (markdown/text/html/attributes), `eval` for arbitrary JavaScript, screenshots, multi-tab management with sticky active tabs, headed/headless mode control, profile management with multi-MCP disambiguation, kill/restart lifecycle with auto-restart detection, console logging per tab, and native dialog handling (alerts, basic-auth, permissions, device choosers). Thoughtful safety design: every DOM action auto-captures a screenshot, structured markdown and the DOM for inspection; credential-shaped pages suppress capture and redact secrets in output (overridable via `SUPERPOWERS_CHROME_ALLOW_CREDENTIAL_CAPTURE=1` — leave it off); mode toggles restart Chrome and lose POST state, so they are warned loudly. Honest caveats: it requires the `mcp__chrome__use_browser` MCP server (obra's chrome-ws bridge) installed in the agent's runtime — the skill teaches the protocol, it doesn't install the driver; Playwright MCP remains the better pick for fresh throwaway instances and screenshots/PDFs. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/obra-superpowers-chrome-browsing
- Fiche en français: https://theskillharbor.com/fr/products/obra-superpowers-chrome-browsing
- Category: Browser Automation
- Price: Free
- Verification: unverified
- Source repo: https://github.com/obra/superpowers-chrome/blob/main/skills/browsing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
