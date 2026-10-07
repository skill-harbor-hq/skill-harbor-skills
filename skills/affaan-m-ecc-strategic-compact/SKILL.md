<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-strategic-compact
description: "Hook-based reminder to run manual /compact at logical task boundaries instead of arbitrary..."
---

# Strategic compact: manual context compaction for Claude Code

Curated by Skill Harbor — @affaan-m's compaction-timing skill for long Claude Code sessions: a PreToolUse hook script that watches two signals — context size (reads the session transcript's usage records and sums input+cache tokens, suggesting `/compact` at window-scaled thresholds: 160k on a 200k window, 250k on a 1M window, re-reminding every 60k more) and tool-call count (default 50, then every 25) — so compaction happens at logical boundaries (research→planning, milestone completed, before a context shift) instead of arbitrary mid-task auto-compaction. Includes a phase-transition decision table (compact after debugging and failed approaches; never mid-implementation), best practices (write the plan to a file first — the task list may not survive, since newer models removed TodoWrite by default), hook setup for `~/.claude/settings.json`, and environment configuration (COMPACT_THRESHOLD, COMPACT_CONTEXT_THRESHOLD, ECC_CONTEXT_WINDOW_TOKENS, CLAUDE_CODE_ENABLE_TODO_TOOLS). Honest caveats: the hook suggests, you decide — it never compacts by itself; files on disk survive compaction, intermediate reasoning does not; listed here with credit to its creator; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-strategic-compact
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-strategic-compact
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/.agents/skills/strategic-compact/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
