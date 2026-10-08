<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-swift-protocol-di-testing
description: "Make Swift testable with Muse: small focused protocols for file system, network and APIs, default..."
---

# Swift Protocol-Based DI for Testing

Curated by Skill Harbor: a pattern guide that makes Swift code testable by abstracting every external dependency behind small, focused protocols. Each protocol handles exactly one concern (file system access, file read/write, bookmark storage and the like), with a production implementation using the real APIs and a mock implementation using in-memory dictionaries plus configurable error properties for testing failure paths. Dependencies are injected with default parameters, so production code reads cleanly while tests swap in mocks. The guide includes full Swift Testing examples: missing-container errors, successful reads, and corrupt-file error handling, plus best practices (single responsibility per protocol, Sendable conformance for actor boundaries, mock external boundaries only, default parameters for production) and anti-patterns (god protocols, mocking internal types, #if DEBUG conditionals instead of real injection, forgetting Sendable, over-engineering types with no external dependencies). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it assumes comfort with Swift concurrency (actors, Sendable); if a type has no external dependencies it needs no protocol at all. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-swift-protocol-di-testing
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-swift-protocol-di-testing
- Category: Swift
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/swift-protocol-di-testing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
