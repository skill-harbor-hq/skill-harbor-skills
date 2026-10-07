<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: samber-golang-troubleshooting
description: "Root-cause debugging for Go: crashes, races, hangs."
---

# Go Troubleshooting Skill for Muse

A systematic Go debugger for Muse: a symptom decision tree (won't compile → build/vet; panics → GOTRACEBACK + race detector; hangs → pprof goroutine dump; CPU spikes → CPU profile; memory growth → heap profile), six Golden Rules (read the error, reproduce first with a failing test, measure don't guess, one hypothesis at a time, root cause not workarounds, trace callers before blaming a function), and deep reference guides on common Go bugs, test-driven debugging, concurrency (races, deadlocks, goroutine leaks via goleak), pprof, GODEBUG tracing, Delve breakpoints, and production debugging without stopping the service. Two modes: sequential single-issue debug, and a codebase bug hunt fanned out to five parallel sub-agents (nil/interface, resources, error handling, races, context/slice/map). Expects a Go toolchain plus Delve (installed via go install). Discovered via skills.sh. Honest note: its discipline is strict by design — no fixes without root-cause investigation first; production profiling requires auth and network isolation on pprof endpoints, and it delegates profile interpretation and benchmarking to the companion golang-benchmark skill, not included here. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/samber-golang-troubleshooting
- Fiche en français: https://theskillharbor.com/fr/products/samber-golang-troubleshooting
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/samber/cc-skills-golang/blob/main/skills/golang-troubleshooting/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
