<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gamedev-skills-awesome-gamedev-agent-skills-game-ui-ux
description: "Design and build game UI/UX that survives every screen — anchor-based responsive layout, resolution..."
---

# Engine-neutral game UI/UX: responsive HUDs, menus, focus navigation

Curated by Skill Harbor — @gamedev-skills's skill for engine-neutral game UI/UX architecture (it owns the architecture and defers the concrete widget API to the engine's UI skill): a 7-step core workflow — anchors + containers, never absolute pixels; a reference-resolution scaling strategy (expand vs letterbox); respect the safe area (notches, TV overscan); make every screen keyboard/gamepad navigable (initial focus, focus neighbors, visible focus highlight); model screens as a push/pop stack (pause over game, resume); drive the HUD from events (`health_changed`, `score_changed`), never per-frame polling; verify across real resolutions and devices, gamepad-only. Patterns with Godot 4.7 and Unity 6.3 LTS examples (Godot anchors presets, Unity RectTransform anchors and CanvasScaler, `DisplayServer.get_display_safe_area()` / `Screen.safeArea`, `grab_focus()` / `EventSystem.SetSelectedGameObject`). A pitfalls list (single design resolution, no aspect-ratio policy, ignored safe area, no initial focus, polling in `_process`/`Update`, tiny fixed fonts, boolean-flag menu flow, hardcoded English strings) and a references file with the full layout-and-flow detail (stretch modes, safe-area math, focus patterns, diegetic vs non-diegetic UI, accessibility, localization-ready layout). Honest caveats: architecture guidance only — concrete widgets, themes and styling come from companion skills (godot-ui-control, Unity UGUI/UI Toolkit) not bundled here; visual juice belongs to `game-feel`...

- Listing: https://theskillharbor.com/products/gamedev-skills-awesome-gamedev-agent-skills-game-ui-ux
- Fiche en français: https://theskillharbor.com/fr/products/gamedev-skills-awesome-gamedev-agent-skills-game-ui-ux
- Category: Game Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/gamedev-skills/awesome-gamedev-agent-skills/blob/main/skills/disciplines/game-ui-ux/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
