<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: software-mansion-argent-argent-native-profiler
description: "Profile a running mobile app for native CPU hotspots, UI hangs and memory leaks, then drill down..."
---

# Native mobile profiler: iOS xctrace and Android Perfetto CPU, hang and leak diagnosis

Curated by Skill Harbor — @software-mansion's Argent native profiler skill (part of the Argent agent toolkit): a strict end-to-end workflow for diagnosing native-level performance issues on mobile. Tools: native-profiler-start/stop (iOS via xctrace, Android via Perfetto with an in-process WASM trace-processor), native-profiler-analyze (bottlenecks as RED/YELLOW by severity: CPU >15%, all UI hangs, attributed leaks), profiler-stack-query (hang stacks, function callers, thread breakdown, leak details), profiler-load (reload previous sessions). Investigation patterns for hangs, CPU hotspots and leaks (including the malloc-stack-logging trick for unattributed iOS leaks), and documented caveats: simulator reflects host-Mac performance not real hardware, xctrace overhead can make Hermes internals look like hotspots, run-to-run variance, live-API data variability, and Android needing a debuggable/profileable app for perf_sample callstacks. Honest caveat: physical iPhone is not supported — use a simulator; iOS needs Xcode command-line tools on PATH. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/software-mansion-argent-argent-native-profiler
- Fiche en français: https://theskillharbor.com/fr/products/software-mansion-argent-argent-native-profiler
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/software-mansion/argent/blob/main/packages/skills/skills/argent-native-profiler/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
