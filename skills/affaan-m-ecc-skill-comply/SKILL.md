<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-skill-comply
description: "Measure whether your agents actually follow the skills, rules, and definitions you gave them, with..."
---

# Skill Comply

Curated by Skill Harbor: an automated compliance measurement workflow for coding agents, from the ECC framework and adaptable to any Claude Code setup. It auto-generates expected behavioral sequences (specs) from any .md file (workflow skills, mandatory rules, agent definitions), builds test scenarios at three prompt strictness levels (supportive, neutral, competing), runs claude -p while capturing tool call traces via stream-json, classifies tool calls against spec steps with an LLM (not regex), checks temporal ordering deterministically, and produces self-contained reports with the spec, the scenario prompts, compliance scores, and full tool call timelines. Run via uv run python -m scripts.run (a no-cost --dry-run mode generates spec plus scenarios only; custom models supported). The key concept is prompt independence: whether a skill or rule is followed even when the prompt does not explicitly support it. From the affaan-m/ECC repository (MIT). Honest caveats: requires the skill's companion scripts and a claude -p style CLI with stream-json output; full runs consume model tokens, so start with --dry-run. Verifying internal agent-definition workflows is not yet supported. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-skill-comply
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-skill-comply
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/skill-comply/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
