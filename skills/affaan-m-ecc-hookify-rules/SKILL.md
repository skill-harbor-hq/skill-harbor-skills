<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-hookify-rules
description: "Add pattern guardrails to Muse with hookify rules: markdown files with YAML frontmatter that warn..."
---

# Hookify Rules

Curated by Skill Harbor: a guide to writing hookify rules, the pattern guardrails that make Muse warn or block itself at exactly the right moment. A rule is a markdown file with YAML frontmatter stored as .claude/hookify.<name>.local.md: name in verb-first kebab-case (warn-*, block-*, require-*), enabled toggle, event type (bash, file, prompt, stop, or all), action warn or block, and a regex pattern or multi-condition set. The guide walks through the frontmatter fields, then the event guide with concrete matches: dangerous bash patterns like rm -rf, dd if=, sudo, and chmod 777; file events for console.log and debugger leftovers, eval and innerHTML risks, and sensitive .env, credentials, and .pem files; stop events for completion checks; prompt events for workflow enforcement. Pattern writing tips cover regex escaping, the classic pitfalls of too-broad (log matches login) versus too-specific patterns, and YAML escaping, with a python3 one-liner to test patterns before deploying them. It also documents the /hookify slash commands to create, list, configure, and get help, plus file organization and the gitignore recommendation for local rules. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is guidance for writing rules, not the hookify runtime itself; over-blocking slows Muse down, start with warn and graduate to block. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-hookify-rules
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-hookify-rules
- Category: Hooks
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/hookify-rules/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
