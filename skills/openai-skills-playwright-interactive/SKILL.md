<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: openai-skills-playwright-interactive
description: "Debug local web or Electron apps with a persistent Playwright js_repl session — short pointer"
---

# Playwright interactive: persistent js_repl browser sessions for UI debugging

Curated by Skill Harbor — ⚠️ **Security warning** — this skill requires Codex with sandboxing DISABLED (`--sandbox danger-full-access`) and the `js_repl` feature enabled; only use it in a workspace you fully trust, and understand the trade-off before you start. A short pointer to @openai's playwright-interactive workflow: keep one persistent Playwright session alive across iterations to debug local web or Electron apps — write a QA inventory from the requirements and implemented behaviors first, run the bootstrap cell once, keep reusing the same handles for renderer reloads and app relaunches, run functional QA with normal user input plus a separate visual QA pass, capture screenshot evidence for every signed-off claim, and reset the kernel only as a recovery tool. Honest caveats: **no license declared in the repository — license unknown**, so this is a short fiche linking to the source, without reusing its content; built for the Codex agent runtime (`js_repl` in `~/.codex/config.toml`), not generic agents. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/openai-skills-playwright-interactive
- Fiche en français: https://theskillharbor.com/fr/products/openai-skills-playwright-interactive
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/openai/skills/blob/main/skills/.curated/playwright-interactive/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
