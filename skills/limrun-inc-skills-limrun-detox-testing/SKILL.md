<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: limrun-inc-skills-limrun-detox-testing
description: "Configure, run and debug Detox E2E tests against Limrun iOS cloud simulators: mediator, tunnel and..."
---

# Run Detox E2E tests on Limrun iOS simulators

Curated by Skill Harbor — @limrun-inc's operational guide for Detox runtime work on Limrun iOS simulators: the three-terminal flow (Detox mediator `detox run-server`, `lim ios tunnel` for destination tunnels, tester launched before the app connects), wiring the `.detoxrc` session environment (`DETOX_SERVER`, `DETOX_SESSION_ID`), the Limrun third-party driver config (`@limrun/detox/driver`) with the maintained `examples/detox-ios` happy path, connection validation signals (`appConnected`/`testerConnected` in mediator logs), accessibility-identifier tips for SwiftUI, and common gotchas (benign "cannot forward" noise, tunnel timeouts, cleanup order) — with the limulator `lim ios` CLI as the control plane. Honest caveats: requires a Limrun account and active iOS simulator instances (the `lim ios` CLI, API URL and token); the agent should re-check `--help` before running commands it hasn't used in-session; MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/limrun-inc-skills-limrun-detox-testing
- Fiche en français: https://theskillharbor.com/fr/products/limrun-inc-skills-limrun-detox-testing
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/limrun-inc/skills/blob/main/skills/limrun-detox-testing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
