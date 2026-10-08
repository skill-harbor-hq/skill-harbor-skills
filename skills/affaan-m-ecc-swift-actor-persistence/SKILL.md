<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-swift-actor-persistence
description: "Thread-safe data persistence in Swift with actors: an in-memory cache plus file-backed storage..."
---

# Swift Actor Persistence

Curated by Skill Harbor: a Swift concurrency pattern that turns thread-safe persistence into a compiler guarantee. The core is a generic actor-based repository: an in-memory dictionary cache for O(1) reads, file-backed JSON storage with atomic writes for durability, all wrapped in a Swift actor so serialized access is enforced by the compiler instead of locks or dispatch queues. The repository is generic over Codable and Identifiable types, with save, delete, find, and loadAll operations. Initialization loads synchronously before actor isolation activates, avoiding the async-init trap. The pattern extends to offline-first apps: local storage as the source of truth, background sync when the network returns, conflict resolution strategies. Also covered: when actors are not enough (large datasets needing SQLite or Core Data), migration from legacy lock-based code, and testing actors with async test functions. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: JSON file storage fits small to medium datasets; for large data or complex queries use a real database; actor isolation adds async boundaries, design your call sites accordingly. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-swift-actor-persistence
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-swift-actor-persistence
- Category: Swift
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/swift-actor-persistence/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
