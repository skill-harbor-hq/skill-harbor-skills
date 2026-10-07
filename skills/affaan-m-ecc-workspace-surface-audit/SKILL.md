<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-workspace-surface-audit
description: "Read-only audit of active repos, MCP servers, plugins, connectors, env surface and tool setup —..."
---

# Workspace surface audit: read-only inventory of your agent setup and what to add next

Curated by Skill Harbor — @affaan-m's read-only audit for your agent workspace and machine: it answers "what can this workspace actually do right now, and what should I add or enable next?" in three phases — inventory everything (repo surface: package.json, `.mcp.json`, `.claude/settings*.json`, `AGENTS.md`; env surface showing only key names like `STRIPE_API_KEY`, never values; installed plugins, connected apps, MCP/LSP servers; existing ECC skills), benchmark against official and installed plugin surfaces (what each does, whether ECC matches it, has only a raw form of it, or fully lacks it), then convert each real gap into the right ECC-native form (repeatable workflow → skill, side effects → hook, delegated role → agent, external bridge → MCP server or connector). Outputs a five-section report: current surface, parity, raw-only gaps, missing integrations, and the top 3–5 next steps by impact. Non-negotiable rules: never print secret values (provider names, key names and file paths only), never modify files unless explicitly asked, and treat external plugins as inspiration — never as the authority. Honest caveats: **the skill is written in Japanese** (lives under `docs/ja-JP/`); it is an ECC-ecosystem skill, so parts of its vocabulary assume you use that setup. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-workspace-surface-audit
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-workspace-surface-audit
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/docs/ja-JP/skills/workspace-surface-audit/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
