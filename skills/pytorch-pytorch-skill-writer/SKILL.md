<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pytorch-pytorch-skill-writer
description: "Create well-structured Agent Skills for Claude Code — scope, location, structure, frontmatter..."
---

# Skill Writer: guide your agent through creating well-structured Agent Skills (short listing)

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @pytorch's skill-writer, a meta-skill that guides an agent through creating well-structured Agent Skills for Claude Code. A 10-step process: determine skill scope (ask clarifying questions, keep one skill to one capability), choose the location (personal `~/.claude/skills/` vs project `.claude/skills/`), create the directory structure, write the SKILL.md frontmatter (name rules — lowercase, hyphens, max 64 chars, must match directory; description formula — what it does plus when to use it, max 1024 chars, with trigger words), write effective descriptions (good vs too-vague examples), structure the content (overview, quick start, instructions, examples, best practices, requirements, advanced usage), add optional supporting files (reference.md, examples.md, scripts/, templates/) with progressive disclosure, validate (file structure, frontmatter, content quality), test (restart Claude Code, ask relevant questions, verify activation), and debug (make descriptions more specific, check location, validate YAML, `claude --debug`). Includes common patterns (read-only skill with allowed-tools, script-based skill, multi-file skill), best practices for authors (one skill one purpose, specific descriptions, concrete examples, list dependencies, test, version, progressive disclosure), and a validation checklist plus troubleshooting section. Honest caveats: written for Claude Code...

- Listing: https://theskillharbor.com/products/pytorch-pytorch-skill-writer
- Fiche en français: https://theskillharbor.com/fr/products/pytorch-pytorch-skill-writer
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/pytorch/pytorch/blob/main/.claude/skills/skill-writer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
