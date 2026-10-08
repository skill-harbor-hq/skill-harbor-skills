<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-latency-critical-systems
description: "Engineering discipline for realtime systems with Muse: track p50/p95/p99, map the hot path..."
---

# Latency-Critical Systems Playbook

Curated by Skill Harbor: an engineering playbook that makes Muse treat latency as a set of separate, measurable quantities instead of one vague "fast". The skill splits the metrics: p50, p95, and p99 latency, throughput, freshness age, queue depth, cache hit rate, provider response time, browser render time, correctness under load, and failure/retry behavior. Then it maps the hot path from source event to user-visible state (source event, provider API, ingest worker, queue, cache, edge route, client stream, browser render) and measures each segment separately, so optimization effort lands where the time actually goes. The optimization order is strict: remove unnecessary round trips first, cache stable reads with freshness metadata, batch small calls, move compute closer to data or user, split hot and cold paths, apply backpressure before queues grow unbounded, use streaming only when it improves freshness, add canaries for stale data and degraded providers. Verification uses live readbacks against the deployed surface: HTTP timing and headers, provider freshness timestamps, queue and edge state, browser verification of actual UI freshness, logs around retries and degraded mode. Hard guardrails: never optimize latency by dropping required validation, never hide stale data behind fast cache hits, never claim millisecond behavior from client labels without measurement, never run live orders, destructive migrations, or customer-impacting deploys without an explicit approval...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-latency-critical-systems
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-latency-critical-systems
- Category: Performance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/latency-critical-systems/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
