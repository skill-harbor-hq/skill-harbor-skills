<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-redis-patterns
description: "Redis best practices for production: data structures, cache-aside, distributed locks, rate..."
---

# Redis Patterns

Curated by Skill Harbor: a quick-reference patterns skill for Redis in production backends. It maps use cases to the right data structure (strings for cache, hashes for sessions, sorted sets for leaderboards, streams for durable queues), then gives working recipes: cache-aside and write-through caching, tag-based invalidation, session storage, fixed-window and atomic sliding-window rate limiting with Lua, distributed locks with SET NX PX plus safe token-checked release, pub/sub for fire-and-forget, and Redis Streams with consumer groups for guaranteed delivery. Key naming conventions, TTL strategy tables, connection pooling, cluster and Sentinel setups, and eviction policies round it out, plus an anti-patterns table (KEYS star in production, keys with no TTL, blobs over 100KB, cache-miss stampedes). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; you need a Redis server to apply any of it, and multi-node locking should use a Redlock-algorithm library rather than hand-rolled SET NX. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-redis-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-redis-patterns
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/redis-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
