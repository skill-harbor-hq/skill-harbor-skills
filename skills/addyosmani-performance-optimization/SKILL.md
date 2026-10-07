<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: addyosmani-performance-optimization
description: "Measure first, fix the real bottleneck, prove the win"
---

# Performance Optimization Skill for Muse

A strict, measurement-first methodology for application performance across frontend, backend, queries, and databases: measure, identify the actual bottleneck, fix it, verify by re-measuring, then guard against regression. Includes a symptom-to-measurement decision tree (slow first load → bundle/TTFB/waterfall; sluggish interaction → main-thread long tasks; slow API → query logs), Core Web Vitals targets, and concrete fixes for the classic anti-patterns — N+1 queries, unbounded data fetching, indexes added without reading the query plan (with EXPLAIN ANALYZE interpretation), connection-pool exhaustion, unoptimized images (art direction + resolution switching), React re-renders, large bundles, and caching done wrong (layer selection, key design so one user's data never leaks to another, single invalidation strategy, stampede guards). Its most distinctive rule: verify with a keep-or-revert verdict — "neutral" is a revert, not a keep — and log every attempt, including the reverted ones, so a dead idea isn't tried again next quarter. Ends with regression guards: synthetic CI budgets plus field (RUM) monitoring on the metric users actually feel. Discovered via skills.sh. Honest note: it is orientation web/backend (React, SQL, Redis, CDN examples) — the method transfers, the idioms need translation on other stacks; and it will not let you "optimize" without a baseline, so there are no instant fixes here, only proven ones. Skill Harbor never reviews the code, review it yourself...

- Listing: https://theskillharbor.com/products/addyosmani-performance-optimization
- Fiche en français: https://theskillharbor.com/fr/products/addyosmani-performance-optimization
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/addyosmani/agent-skills/blob/main/skills/performance-optimization/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
