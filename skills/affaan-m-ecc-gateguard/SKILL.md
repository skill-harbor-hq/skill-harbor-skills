<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-gateguard
description: "A PreToolUse hook that blocks Claude's first Edit, Write, or Bash attempt until the agent presents..."
---

# GateGuard Fact-Forcing Pre-Action Gate

Curated by Skill Harbor: a PreToolUse hook that fixes the most expensive Claude Code failure mode, the agent that edits before investigating. Instead of asking the model to self-evaluate ("are you sure?", which always gets "yes"), GateGuard runs a three-stage gate: DENY the first Edit/Write/Bash attempt, FORCE the model to gather specific facts, ALLOW the retry once the facts are presented. The Edit/MultiEdit gate demands the full list of files importing the target, the affected public functions, and the data file schema with redacted values; the Write gate demands proof no existing file serves the same purpose; the destructive Bash gate triggers on every rm -rf, git reset --hard, git push --force, or drop table and demands a one-line rollback procedure plus the verbatim user instruction. Two independent A/B tests measured +2.25 average quality points, with the difference showing in design depth, not just passing tests. Graduated controls via environment variables: ECC_GATEGUARD=off disables it entirely, GATEGUARD_EXEMPT_GLOBS skips low-signal trees like tests or generated artifacts, GATEGUARD_BASH_ROUTINE_DISABLED narrows to destructive commands only. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: hooks see tool calls one at a time, so in a parallel batch the first call is denied while siblings may already apply; send dependent edits to an untouched file sequentially and re-read after a denial. Tune exemptions...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-gateguard
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-gateguard
- Category: Claude Code
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/gateguard/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
