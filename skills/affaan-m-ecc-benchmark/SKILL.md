<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-benchmark
description: "Measure performance baselines before and after a PR: browser Core Web Vitals, API latency..."
---

# Benchmark, Performance Baseline and Regression Detection

Curated by Skill Harbor: measure performance baselines and detect regressions across three modes. Mode 1, page performance, measures real browser metrics via browser MCP: Core Web Vitals (LCP target under 2.5s, CLS under 0.1, INP under 200ms, plus FCP and TTFB), resource sizes (total page weight target under 1MB, JS bundle under 200KB gzipped, CSS, images, third-party scripts), network request counts, and render-blocking resources. Mode 2, API performance, hits each endpoint 100 times and measures p50, p95, p99 latency plus response size and status codes. Mode 3 covers build and test feedback times. Before/after comparisons are stored in git-tracked `.ecc/benchmarks` JSON, so a PR's performance impact is reviewable like code. Use when checking page speed, responding to "it feels slow" reports, verifying launch performance targets, or comparing stack alternatives. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: page metrics need a browser MCP available; synthetic lab numbers are not real-user data, treat them as direction not verdict. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-benchmark
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-benchmark
- Category: Performance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/benchmark/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
