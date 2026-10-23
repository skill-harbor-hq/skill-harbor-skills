<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: test-flakiness
description: "INTEGRATED SYSTEM: this skill belongs to the complete \"Claude Code Game Studios\" template (49..."
---

# Test Flakiness

INTEGRATED SYSTEM: this skill belongs to the complete "Claude Code Game Studios" template (49 agents, 74 skills, templates and a studio CLAUDE.md); it assumes that template and its conventions. This listing installs only this skill's folder, without the rest of the system, and the skill may reference template agents or files that are absent outside the full template. It detects flaky tests from locally stored CI logs and result XML (JUnit/NUnit/plain text), aggregates pass rates across runs (findings under 3 runs are only 'suspected'), classifies likely causes, and recommends quarantine or fixes; it asks separately before appending to the tests/regression-suite.md quarantine section and before writing the optional flakiness report; it never deletes test files and connects to no CI service.

- Listing: https://theskillharbor.com/products/test-flakiness
- Fiche en français: https://theskillharbor.com/fr/products/test-flakiness
- Category: Games
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Donchitos/Claude-Code-Game-Studios/blob/main/.claude/skills/test-flakiness/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
