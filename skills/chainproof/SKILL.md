<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: chainproof
description: "Local, verifiable memory for AI agents"
---

# ChainProof

Curated by Skill Harbor — ChainProof is local-first continuity and provenance infrastructure for AI agents: a single Go binary that turns everything an agent does (inputs, tool calls, file changes, outputs, failures) into a durable, searchable evidence trail anchored in a hash chain you can verify without trusting any server. Run it on your own machine, wrap Codex, Claude Code, OpenClaw or any local harness, and resume work from verified checkpoints instead of a stale transcript. Open source (MIT) by @vajramatt — no account, no API key, no hosted service; your ledger never leaves your machine. Spotted in an r/AIAgentsInAction comment by u/DarkSolarWarrior.

⚠️ Security warning: the project's README suggests installing via curl|sh. This listing's install steps deliberately avoid that pattern (build from source or go install instead) — review the install script yourself before ever piping it to a shell.

Honest caveats: very new third-party project (repo created August 2026, zero stars at listing time); multi-host coordination and signed attestations are roadmap items, not shipped features; the local HTTP API accepts loopback connections only and has no authentication — never expose it publicly. Note: this is local CLI infrastructure an agent drives, not a copy-paste Muse skill. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/chainproof
- Fiche en français: https://theskillharbor.com/fr/products/chainproof
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/vajramatt/chainproof

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
