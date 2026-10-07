<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: tradermonty-claude-trading-skills-skill-designer
description: "Turn a JSON skill idea into a complete skill directory — a prompt builder plus validation — that..."
---

# Skill designer: generate new skills from structured idea specs

⚠️ **Trading warning / Avertissement trading** — this skill powers an auto-generation pipeline for trading-analysis skills; trading with real money is risky, nothing in this skill places trades, and Skill Harbor provides no financial advice. Curated by Skill Harbor — @tradermonty's meta skill: it doesn't trade itself, it designs other skills. It turns a structured skill-idea specification (title, description, category like trading-analysis) into a complete Claude CLI prompt that instructs Claude to create a full skill directory — SKILL.md with YAML frontmatter, reference documents, helper scripts, and test scaffolding — following the repository conventions. The workflow: prepare the idea JSON (--idea-json) with a normalized skill name (--skill-name); run the prompt builder (python3 skills/skill-designer/scripts/build_design_prompt.py), which loads the idea, reads the three reference files (skill-structure-guide, quality-checklist with the dual-axis reviewer's 5-category 100-point rubric, skill-template), and lists existing skills to prevent duplication; pipe the resulting prompt into claude -p (--allowedTools Read,Edit,Write,Glob,Grep); then validate the output (frontmatter, directory structure, dual-axis-skill-reviewer score threshold). Honest caveats: it needs Python 3.9+, the repo's references/ files in place, and the Claude CLI; the generated skills land in the claude-trading-skills repo — expect them to be trading-oriented by design, and review generated code before...

- Listing: https://theskillharbor.com/products/tradermonty-claude-trading-skills-skill-designer
- Fiche en français: https://theskillharbor.com/fr/products/tradermonty-claude-trading-skills-skill-designer
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tradermonty/claude-trading-skills/blob/main/skills/skill-designer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
