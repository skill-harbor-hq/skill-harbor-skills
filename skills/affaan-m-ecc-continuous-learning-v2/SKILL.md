<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-continuous-learning-v2
description: "Turn Claude Code sessions into reusable instincts: hook-observed, confidence-scored, project-scoped..."
---

# Continuous Learning v2

Curated by Skill Harbor: an instinct-based learning system that turns Claude Code sessions into reusable knowledge, from the ECC framework and usable by any Claude Code user with hooks. Hooks (PreToolUse/PostToolUse) capture prompts and tool calls with 100% reliability (the v1 skill-based observation only fired 50 to 80% of the time); a background Haiku observer agent detects patterns (user corrections, error resolutions, repeated workflows) and creates atomic instincts: one trigger, one action, confidence-weighted from 0.3 (tentative) to 0.9 (near-certain), domain-tagged, evidence-backed. v2.1 adds project scoping: instincts are isolated per project (detected via git remote URL or repo path, 12-character hash IDs), so React patterns stay in the React project and Python conventions stay in the Python project; an instinct seen in 2+ projects at 0.8+ confidence becomes a promotion candidate to global scope. Instincts cluster into full skills, commands, or agents via /evolve; export and import supported. Observations stay local on your machine; only patterns (never raw observations or code) can be exported. From the affaan-m/ECC repository (MIT). Honest caveats: requires Claude Code hooks; install as a plugin (Claude Code v2.1+ auto-loads hooks.json) or wire observe.sh manually into settings.json. The background observer needs WSL2, Linux, or macOS; on native Windows it is effectively a no-op. The observer is disabled by default and consumes tokens when enabled. Skill Harbor...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-continuous-learning-v2
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-continuous-learning-v2
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/continuous-learning-v2/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
