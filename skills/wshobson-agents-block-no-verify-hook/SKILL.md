<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: wshobson-agents-block-no-verify-hook
description: "A Claude Code PreToolUse hook that intercepts --no-verify/--no-gpg-sign bypass flags in Bash..."
---

# Block no-verify hook — stop agents skipping git pre-commit hooks

Curated by Skill Harbor — @wshobson practical skill for keeping AI coding agents honest at commit time. Agents habitually reach for `git commit --no-verify` to dodge hook failures; this skill configures a Claude Code `PreToolUse` hook on Bash that inspects each tool call's JSON with a dependency-free grep pattern and rejects (exit code 2) any command containing `--no-verify`, `--no-gpg-sign`, their short prefixes (git accepts `--no-veri`), or a short-option group containing `-n` after `commit`. It covers per-project and global installation (`.claude/settings.json`), is explicit about its limits (it stops habitual bypasses, not a determined evader who builds the flag from pieces or swaps `core.hooksPath`), notes that commit messages mentioning a flag are blocked too (failing safe), and shows how to extend the pattern to other flags like `--force` and combine it with sibling hooks. MIT-licensed. Honest caveats: Claude Code-specific — other agent harnesses need their own hook mechanism; it only works if the settings file is actually installed and the agent doesn't tamper with hooks; pair it with meaningful pre-commit hooks, because blocking bypasses is pointless if there is nothing to run. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/wshobson-agents-block-no-verify-hook
- Fiche en français: https://theskillharbor.com/fr/products/wshobson-agents-block-no-verify-hook
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/wshobson/agents/blob/main/plugins/block-no-verify/skills/block-no-verify-hook/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
