<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: team-release
description: "INTEGRATED SYSTEM: this skill belongs to the complete \"Claude Code Game Studios\" template (49..."
---

# Team Release

INTEGRATED SYSTEM: this skill belongs to the complete "Claude Code Game Studios" template (49 agents, 74 skills, templates and a studio CLAUDE.md); it assumes that template and its conventions. This listing installs only this skill's folder, without the rest of the system, and the skill may reference template agents or files that are absent outside the full template. It orchestrates the release team from candidate to deployment: a stage check first (/gate-check release must have set project.stage to Release, or the run stops; an override needs the user's recorded reason), release planning, a version-bump candidate on main, parallel quality, security, netcode, localization, performance and analytics sign-offs, a producer go/no-go (a NO-GO skips deployment entirely), then — only after its own explicit approval question in every automation mode, staging-only offered — tagging, staging deployment, production deployment and patch notes, and post-release monitoring and publication of the launch communication. At the default team size only the release-manager runs; the full pipeline names ten agents. Records land under production/releases/ under a documented bounded exception; sub-skills ask before writing.

- Listing: https://theskillharbor.com/products/team-release
- Fiche en français: https://theskillharbor.com/fr/products/team-release
- Category: Games
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Donchitos/Claude-Code-Game-Studios/blob/main/.claude/skills/team-release/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
