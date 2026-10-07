<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-swift-concurrency-6-2
description: "Swift 6.2 Approachable Concurrency patterns: single-threaded by default, explicit @concurrent..."
---

# Swift 6.2 Concurrency

Curated by Skill Harbor: patterns for adopting Swift 6.2's Approachable Concurrency, where async code stays single-threaded by default and concurrency becomes explicit. In Swift 6.1 and earlier, async functions could be implicitly offloaded to background threads, producing data-race errors even in seemingly safe MainActor code; 6.2 fixes this, and @concurrent marks the deliberate offloads. The skill covers the core patterns: isolated conformances so MainActor types can safely conform to non-isolated protocols, offloading CPU-intensive work with @concurrent, designing MainActor-based app architecture, resolving data-race safety compiler errors, and migrating Swift 5.x or 6.0/6.1 projects, including the Xcode 26 build settings that enable the new model. Each pattern shows the 6.1 error next to the 6.2 fix so the change is concrete. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: Swift 6.2 features need Xcode 26; concurrency is still easy to misuse, the compiler catches races, not logic errors; migrating a large codebase takes incremental passes. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-swift-concurrency-6-2
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-swift-concurrency-6-2
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/swift-concurrency-6-2/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
