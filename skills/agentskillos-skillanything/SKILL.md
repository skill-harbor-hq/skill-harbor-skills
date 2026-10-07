<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: agentskillos-skillanything
description: "Turn any software, API, or CLI into a production-ready AI skill with a 7-phase automated pipeline."
---

# SkillAnything

Curated by Skill Harbor: a skill that builds skills. Point SkillAnything at a target (an API, a CLI, a library, a workflow, a web service) and it runs a seven-phase pipeline: analyze the target and extract its capabilities, design the skill architecture, implement the SKILL.md plus scripts and references, generate eval test cases, benchmark with-skill against baseline, optimize the skill description with a train/test loop, and package the result for Claude Code, OpenClaw, Codex, or a generic .skill zip. It ships an eval system modeled on Anthropic's skill-creator, with a grader agent, a comparator agent for blind A/B output checks, and an interactive HTML review viewer; the eval loop can be skipped for quick prototypes, and an interactive mode pauses after each phase for your review. By @AgentSkillOS, listed here with credit to its creator. Honest caveats: a generated skill is only as good as the target's documentation; single-phase mode exposes each step individually (analyze, design, generate tests, run eval, package) if you prefer control over full automation; and the PyArmor obfuscation option exists but is off by default. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/agentskillos-skillanything
- Fiche en français: https://theskillharbor.com/fr/products/agentskillos-skillanything
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/AgentSkillOS/SkillAnything

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
