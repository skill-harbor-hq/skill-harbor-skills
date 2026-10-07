<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: grafana-skills-k6-perf-test-website
description: "Elicit workflows, record with Playwright, build hybrid (protocol + browser) k6 suites with SLO..."
---

# End-to-end k6 performance testing for websites, with Grafana backend investigation

Curated by Skill Harbor — @grafana's official end-to-end workflow for performance-testing a website with k6: Step 1 (the most important), elicit real user workflows from the user — the skill stops rather than guessing. Then scaffold the project, record each workflow with Playwright into a HAR, convert to k6 protocol scripts, and build functional tests that must be green before any load testing. Next, design SLO-backed thresholds (global, per-endpoint tagged, per-iteration, Web Vitals LCP/INP/CLS), and build hybrid load tests — a protocol scenario driving load plus one browser VU measuring Web Vitals under load — for smoke, average, stress, spike, soak and breakpoint. A load-generator monitor sidecar guards against "the laptop is the bottleneck" false readings; cloud runs dispatch to Grafana Cloud k6; the backend is investigated via Grafana (RED metrics, logs, traces, Pyroscope) only when the user owns it; everything lands in a structured Markdown report. Hard opinions: always monitor the load generator, local for validation / cloud for scale, no shared test libs. Honest caveats: toolchain prerequisites — k6 ≥ 2.0, Node.js 20+, Playwright with Chromium, har-to-k6; Grafana Cloud k6 runs are billed (browser VU-hours cost 10× protocol VU-hours — check limits before soak/breakpoint); only ever load-test sites you own or have explicit permission to test. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/grafana-skills-k6-perf-test-website
- Fiche en français: https://theskillharbor.com/fr/products/grafana-skills-k6-perf-test-website
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/grafana/skills/blob/main/skills/grafana-k6/k6-perf-test-website/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
