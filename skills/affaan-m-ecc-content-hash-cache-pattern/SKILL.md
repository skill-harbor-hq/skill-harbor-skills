<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-content-hash-cache-pattern
description: "Cache expensive file-processing results with SHA-256 content-hash keys — path-independent and..."
---

# Content-hash file cache pattern

Curated by Skill Harbor — a design-pattern guide by @affaan-m that teaches an agent how to cache expensive file-processing results (PDF parsing, text extraction, image analysis) using SHA-256 content hashes as cache keys. Unlike path-based caching, a file move or rename is still a cache hit and any content change invalidates automatically. Covers the chunked hashing helper, a frozen-dataclass cache entry, O(1) file storage as `{hash}.json`, graceful handling of corrupted entries (treated as misses), and a service-layer wrapper that keeps the extraction function pure. Includes explicit when-to-use / when-NOT-to-use guidance and common anti-patterns. Credit to its creator. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-content-hash-cache-pattern
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-content-hash-cache-pattern
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/.kiro/skills/content-hash-cache-pattern/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
