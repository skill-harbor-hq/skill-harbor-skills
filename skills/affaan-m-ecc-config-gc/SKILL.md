<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-config-gc
description: "Scan ~/.claude for stale skills, hooks, permissions, MCP servers and caches, then walk through..."
---

# Config GC — garbage collection for your Claude Code configuration

Curated by Skill Harbor — @affaan-m's Config GC: garbage collection for a Claude Code setup. It scans eight accumulation channels — skills, memory files, hooks, permission entries, MCP servers, scheduled reminders/jobs, project history and runtime caches — for redundant, stale, orphaned or low-value items, ranks candidates by confidence, and walks the user through a confirm-one-by-one cleanup (no "yes to all" shortcut). The design is deliberately safe: soft-delete first (`.disabled` renames, `_gc_trash/<date>/` moves), settings JSON is backed up before permission entries are pruned with `jq`, and every run is logged to `~/.claude/gc_log.md` with undo instructions. Includes ready-made scan commands (orphan hook scripts, redundant permission entries, largest stale caches) and an anti-pattern list (bulk approval, hard-deleting on first pass, treating "old" as "dead"). Honest caveats: methodology + shell commands, no binaries — it only works on a Claude Code setup; it never deletes autonomously by design (a human confirms each item), and it never touches anything outside `~/.claude`. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-config-gc
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-config-gc
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/skills/config-gc/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
