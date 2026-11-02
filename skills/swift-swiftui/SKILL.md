<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: swift-swiftui
description: "Swift 6 and SwiftUI code rules for Mac apps, aiming for zero warnings."
---

# swift-swiftui

swift-swiftui sets main-actor default isolation as the template: every type and function runs on the main actor unless stated otherwise, with CPU-heavy pure work in nonisolated concurrent functions, shared mutable state off the main thread in an actor, and C callbacks hopping back with a MainActor task. Data crossing actors must be Sendable, and concurrency errors are fixed at their type, not with unchecked Sendable or nonisolated(unsafe), which are a last resort with a comment explaining why. It warns about a runtime trap the compiler misses: a closure created inside a MainActor type and passed to an API without a Sendable closure parameter inherits the main actor and crashes the app when it runs on a background queue. For state, it uses Observable classes, State in the owning view, Bindable for bindings, and environment sharing, and it warns never to use ForEach over bindings for deletable data. SwiftData rules cover Model classes, model containers, queries, default values for new properties, a stable UUID per model, and manual undo registration. Menu commands get a working pattern, because SwiftUI Commands do not observe Observable models: mirror the selection into a small ObservableObject observed in the App. It also lists type names Swift already uses that must never be reused, AppKit bridges for floating panels, custom text views, status items, and event monitors, and fixes for common compiler and Swift 6 errors. Done when the app builds with zero warnings in Swift 6...

- Listing: https://theskillharbor.com/products/swift-swiftui
- Fiche en français: https://theskillharbor.com/fr/products/swift-swiftui
- Category: Development
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
