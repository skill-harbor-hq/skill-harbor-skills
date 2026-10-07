<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: software-mansion-argent-argent-android-emulator-setup
description: "Boot, connect, and drive Android emulators (and leanback TV AVDs) through the Argent MCP device..."
---

# Argent Android emulator setup: boot and connect devices for UI automation

Curated by Skill Harbor — @software-mansion's Argent skill for getting an Android emulator ready before any UI interaction: find a ready device via `list-devices`, boot an AVD with `boot-device` (automatic hot-boot from snapshots with cold-boot fallback, process cleanup on failure), wire Metro with `adb reverse` for React Native, then drive the device through the unified interaction tools using the Android serial as `udid`. Honest caveats: requires Android SDK Platform Tools (adb) and the Android Emulator on PATH plus a pre-created AVD; leanback Android TV AVDs are focus-driven, not touch-driven (use the focus-driven tools and the `argent-tv-interact` skill); `describe` returns a shallower tree on Android; never hard-kill qemu — dirty images hang cold boots. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/software-mansion-argent-argent-android-emulator-setup
- Fiche en français: https://theskillharbor.com/fr/products/software-mansion-argent-argent-android-emulator-setup
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/software-mansion/argent/blob/main/packages/skills/skills/argent-android-emulator-setup/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
