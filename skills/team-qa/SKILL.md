<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: team-qa
description: "INTEGRATED SYSTEM: this skill belongs to the complete \"Claude Code Game Studios\" template (49..."
---

# Team QA

INTEGRATED SYSTEM: this skill belongs to the complete "Claude Code Game Studios" template (49 agents, 74 skills, templates and a studio CLAUDE.md); it assumes that template and its conventions. This listing installs only this skill's folder, without the rest of the system, and the skill may reference template agents or files that are absent outside the full template. It orchestrates the two-agent QA team through a full testing cycle: context and open-bug loading, a qa-lead strategy gated on the latest existing smoke-check report (a FAIL stops the cycle), a test plan written only after asking, per-story test cases, manual QA that records only results the tester actually gives, bug filing on failures, retained screenshot evidence for Visual/Feel and UI stories, and a sign-off under strict verdict rules (an open S1/S2 is NOT APPROVED; missing evidence is NOT ASSESSED, never a pass). Disclosed: at the end of a run the orchestrator silently appends a one-line QA RUN comment to production/session-state/active.md, without asking. At the default team size the qa-tester runs with the qa-lead at phase gates only.

- Listing: https://theskillharbor.com/products/team-qa
- Fiche en français: https://theskillharbor.com/fr/products/team-qa
- Category: Games
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Donchitos/Claude-Code-Game-Studios/blob/main/.claude/skills/team-qa/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
