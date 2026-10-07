<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-safety-guard
description: "Block destructive ops before they run — rm -rf, git push --force, DROP TABLE, kubectl delete — plus..."
---

# Safety guard against destructive commands in production and autonomous agents

Curated by Skill Harbor — @affaan-m's safety guard for working in production systems or running agents autonomously. Three protection modes: Careful mode detects destructive commands before execution and warns with confirmation plus a safer alternative (watched patterns include `rm -rf` — especially on `/`, `~` or the project root — `git push --force`, `git reset --hard`, `git checkout .`, `DROP TABLE`/`DROP DATABASE`, `docker system prune`, `kubectl delete`, `chmod 777`, `sudo rm`, `npm publish` against accidental publishes, and any command with `--no-verify`); Freeze mode locks file edits to one directory tree (`/safety-guard freeze src/components/` — writes outside it are blocked with explanation), useful to keep an agent focused on one area; Guard mode combines both for maximum safety with autonomous agents (read everything, write only in the allowed directory). The implementation uses PreToolUse hooks on Bash, Write, Edit and MultiEdit calls, logs every blocked action to `~/.claude/safety-guard.log`, and integrates with full-auto agent sessions and ECC 2.0 observability risk scoring. Honest caveats: **the skill is written in Japanese** (lives under `docs/ja-JP/`); it describes a hook-based design — wiring it into your agent harness is your own setup work; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-safety-guard
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-safety-guard
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/docs/ja-JP/skills/safety-guard/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
