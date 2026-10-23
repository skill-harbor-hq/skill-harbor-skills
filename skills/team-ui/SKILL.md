<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: team-ui
description: "INTEGRATED SYSTEM: this skill belongs to the complete \"Claude Code Game Studios\" template (49..."
---

# Team UI

INTEGRATED SYSTEM: this skill belongs to the complete "Claude Code Game Studios" template (49 agents, 74 skills, templates and a studio CLAUDE.md); it assumes that template and its conventions. This listing installs only this skill's folder, without the rest of the system, and the skill may reference template agents or files that are absent outside the full template. It orchestrates the UI team through the whole UX pipeline: context gathering that reports each of its five inputs present or absent (a missing committed accessibility tier can never silently pass — it is reported NOT ASSESSED downstream), UX spec authoring via /ux-design, a /ux-review gate that blocks visual design until APPROVED, visual design, engine UI guidance and implementation (UI never owns game state, all text through localization, keyboard/mouse and gamepad), three parallel reviews, and polish. At the default team size the ui-programmer and ux-designer run; wider sizes add the art-director, accessibility-specialist and engine UI specialist. Working artifacts go under production/ui/[feature-name]/ under a documented bounded exception; implementation code needs one ask, and the /ux-design sub-skill asks before writing.

- Listing: https://theskillharbor.com/products/team-ui
- Fiche en français: https://theskillharbor.com/fr/products/team-ui
- Category: Games
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Donchitos/Claude-Code-Game-Studios/blob/main/.claude/skills/team-ui/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
