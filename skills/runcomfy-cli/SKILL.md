<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: runcomfy-cli
description: "Foundation skill for the runcomfy CLI — install, authenticate, discover model schemas, invoke..."
---

# RunComfy CLI

💳 Paid API required — Curated by Skill Harbor — the foundation skill every other `runcomfy-*` skill builds on: one binary, one auth, hundreds of model endpoints. It teaches the agent to install the CLI (`npm i -g @runcomfy/cli` or zero-install `npx -y @runcomfy/cli`), sign in via the device-code flow (`runcomfy login`, token stored at `~/.config/runcomfy/token.json` with mode 0600, or `RUNCOMFY_TOKEN` in CI), discover model schemas through the catalog (featured models, brand collections like flux-kontext, kling, wan-models, and capability tags like lip-sync and character-swap), and run the full lifecycle — `runcomfy run <vendor>/<model>/<endpoint> --input '<JSON>' --output-dir`, status polling, `--no-wait` submit-then-poll, JSON output mode for scripting, batch loops from a prompt file, and retry-on-75 shell patterns. It also documents the exit-code table (0 success, 64 bad args, 65 schema mismatch, 69 upstream 5xx, 75 retryable, 77 not signed in, 130 interrupted with remote cancel) and the security model: no shell-injection surface from prompt content, outbound calls restricted to `model-api.runcomfy.net` and `*.runcomfy.net`, a 2 GiB per-download cap, and a warning never to pipe the standalone curl installer into a shell unreviewed. By @genmedia-labs, listed here with credit to its creator. Requires a RunComfy account with paid generation credits — the skill itself is free, but every model call it runs is billed. The skill runs shell commands (declared as `Bash(runcomfy...

- Listing: https://theskillharbor.com/products/runcomfy-cli
- Fiche en français: https://theskillharbor.com/fr/products/runcomfy-cli
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/genmedia-labs/skills/blob/main/runcomfy-cli/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
