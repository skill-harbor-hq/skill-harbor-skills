<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pixijs-pixijs-skills-pixijs-events
description: "Handle pointer, mouse, touch and wheel input in PixiJS v8: eventMode values, FederatedEvent types..."
---

# PixiJS events: pointer, mouse, touch and wheel input done right in PixiJS v8

Curated by Skill Harbor — the official @pixijs skill for handling input in PixiJS v8: pointer, mouse, touch and wheel events done right. Covers the five `eventMode` values (none, passive, auto, static, dynamic) and when each applies (static for buttons and drag targets, dynamic only for objects moving under a stationary cursor), FederatedEvent/FederatedPointerEvent types with their rich fields (global/client points, pointerType, pointerId, pressure, buttons, modifier keys), propagation and capture-phase listeners, custom `hitArea` shapes (Rectangle, Circle, Polygon, or custom `contains()`), cursor styling per object, and `globalpointermove`-based drag patterns. Also covers `eventFeatures` toggles for performance (disabling unused move/click/wheel categories), and a "Common Mistakes" section with HIGH-severity fixes: default eventMode is passive (listeners silently do nothing), `buttonMode` was removed in v8 (use `cursor = 'pointer'`), and v8 move events only fire over the object (use global move events for drag). Ships quick-start code, related-skills pointers (pixijs-accessibility, pixijs-scene-dom-container, pixijs-performance), and API reference links. Honest caveats: PixiJS v8 only — v7 event behavior differs on several points covered here, so don't apply these patterns to older projects without checking. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/pixijs-pixijs-skills-pixijs-events
- Fiche en français: https://theskillharbor.com/fr/products/pixijs-pixijs-skills-pixijs-events
- Category: Game Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/pixijs/pixijs-skills/blob/main/skills/pixijs-events/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
