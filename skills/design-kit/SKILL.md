<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: design-kit
description: "A custom SwiftUI design system with your own parts, tokens, and gallery."
---

# design-kit

design-kit starts from a simple distinction: a native look comes from Apple's parts, while a custom look comes from your own parts, your sidebar row, your button, your checkbox, your icons. Most apps keep Apple's parts and only pick an accent color; a kit is built when the parts themselves must change. Everything lives in Sources/<App>/DesignKit. First, write a spec from the kit-spec template: three words for the feel, the tokens, the type scale, the icon rules, and one section per part with its sizes and states. Then tokens in three layers: a palette of raw colors, a meaning layer with light and dark values each, and scales for type, metrics, and motion, so a rebrand changes only the palette and a dark mode fix changes only the meaning layer. Type styles are named by role, never by size. Views name a KitIcon, never an SF Symbol or a file, so the whole set can change in one place. Each part is a real control, styled with a ButtonStyle, ToggleStyle, or TextFieldStyle, never a shape with a tap gesture, and it has every state (rest, hover, pressed, selected, focused, disabled) in light and dark, plus a forced state for the gallery. For a fully custom look, the title bar is hidden and a custom top bar is drawn, while traffic lights, menus, context menus, sheets, and alerts stay native. A gallery page shows every part in every state in light and dark, and the app shows it instead of its pages when APP_KIT_GALLERY=1 is set. Done when the spec covers every part, every part is a...

- Listing: https://theskillharbor.com/products/design-kit
- Fiche en français: https://theskillharbor.com/fr/products/design-kit
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/daveebbelaar/bama

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
