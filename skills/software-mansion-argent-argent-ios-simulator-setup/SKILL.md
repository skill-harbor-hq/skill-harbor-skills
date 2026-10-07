<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: software-mansion-argent-argent-ios-simulator-setup
description: "Set up and connect to an iOS simulator using Argent MCP tools before any simulator task"
---

# Argent iOS simulator setup

Curated by Skill Harbor — a compact setup skill from @software-mansion's Argent project: the two-step routine to run before any iOS simulator interaction — find a booted simulator (or boot one via `boot-device`), then verify the connection — using Argent's MCP tools (`list-devices`, `gesture-tap`, `gesture-swipe`, etc., which auto-start the server), with the note that sub-agents need MCP permissions and that physical devices are never simulator targets. Honest caveats: **requires the Argent toolchain and MCP permissions to do anything** — the skill is a connection routine, not the tooling itself; assumes a macOS + Xcode environment with simulators installed; Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/software-mansion-argent-argent-ios-simulator-setup
- Fiche en français: https://theskillharbor.com/fr/products/software-mansion-argent-argent-ios-simulator-setup
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/software-mansion/argent/blob/main/packages/skills/skills/argent-ios-simulator-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
