<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: tech-debt
description: "INTEGRATED SYSTEM: this skill belongs to the complete \"Claude Code Game Studios\" template (49..."
---

# Tech Debt

INTEGRATED SYSTEM: this skill belongs to the complete "Claude Code Game Studios" template (49 agents, 74 skills, templates and a studio CLAUDE.md); it assumes that template and its conventions. This listing installs only this skill's folder, without the rest of the system, and the skill may reference template agents or files that are absent outside the full template. It tracks technical debt in four modes: scan (greps the code root for TODO, FIXME, HACK, @deprecated markers, duplication and oversized files and functions, categorised into six debt types — a zero-file code root is reported NOT ASSESSED, never a clean scan), add (a manual entry with category, effort and impact), prioritize (impact-over-effort scoring and re-sorting) and report (a read-only summary that flags items older than three sprints). It spawns no agent. Its only write target is docs/tech-debt-register.md, always after asking, updated never overwritten, with match-before-appending deduplication; the register format is shared with the template's /story-done.

- Listing: https://theskillharbor.com/products/tech-debt
- Fiche en français: https://theskillharbor.com/fr/products/tech-debt
- Category: Games
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Donchitos/Claude-Code-Game-Studios/blob/main/.claude/skills/tech-debt/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
