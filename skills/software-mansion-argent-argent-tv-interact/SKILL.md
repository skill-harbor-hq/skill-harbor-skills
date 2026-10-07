<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: software-mansion-argent-argent-tv-interact
description: "Control and inspect TV apps via focus-driven remote navigation: describe focus, D-pad moves..."
---

# Argent TV — drive Apple TV, Android TV, Fire TV from an agent

Curated by Skill Harbor — a TV-automation skill by @software-mansion (part of the Argent toolkit) that lets an agent control and inspect apps on Apple TV (tvOS simulator), Android TV (leanback emulator), and Amazon Fire TV (Vega VVD). The core rule: a TV is focus-driven, not touch-driven — drive every interaction with `describe` + `tv-remote` + `keyboard`, never coordinate taps. Covers the navigation loop (describe → move focus with single or pathed D-pad presses → re-describe), typing into focused fields, app launch/restart/reinstall, screenshots, per-platform notes (tvOS HID daemon behavior, leanback RN focus-engine blind spots, Vega VVD lifecycle and Debug-vs-Release constraints), Fast Refresh via Metro, and Vega JS-runtime debugging (connect, evaluate, console logs, network inspector) with the honest list of legacy-Hermes limitations. Honest caveats: requires the Argent CLI/tooling installed and targets bootable emulators/simulators/VVDs — not physical TVs by default; Vega component-tree/profiler tools are hard-blocked by its legacy Hermes inspector. Credit to its creator. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/software-mansion-argent-argent-tv-interact
- Fiche en français: https://theskillharbor.com/fr/products/software-mansion-argent-argent-tv-interact
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/software-mansion/argent/blob/main/packages/skills/skills/argent-tv-interact/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
