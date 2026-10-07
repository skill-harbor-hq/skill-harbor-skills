<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-skill-stocktake
description: "Audit installed Claude skills with a fast changed-only scan or a full..."
---

# Skill inventory and quality audit command

Curated by Skill Harbor — @affaan-m's `/skill-stocktake` slash command for auditing every installed Claude skill and command: two modes — a fast scan that re-evaluates only skills changed since the last run (via `results.json` diff, 5–10 minutes), or a full stocktake (20–30 minutes) with a phase-1 inventory of global and project skill paths, a phase-2 quality evaluation where chunked subagents apply a checklist (no overlap with other skills or MEMORY.md/CLAUDE.md, technical references still current, usage frequency considered) and return blind verdicts per skill — Keep, Improve, Update, Retire, or Merge into a named target — each with a self-contained, evidence-backed reason, then a phase-3 summary table and a phase-4 integration pass. Retirement and merge actions always require the user's explicit confirmation, results persist in `results.json` with resume support, and verdicts are blind to skill origin. Honest caveats: **the skill is written in Japanese** (lives under `docs/ja-JP/`); it runs bundled bash scripts and spawns subagents, so review what it will touch before a full run. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-skill-stocktake
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-skill-stocktake
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/docs/ja-JP/skills/skill-stocktake/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
