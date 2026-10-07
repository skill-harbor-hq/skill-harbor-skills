<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: samber-golang-benchmark
description: "Statistically sound Go benchmarks, profiles, CI gating."
---

# Go Benchmarking Skill for Muse

The measurement side of Go performance work: writing benchmarks (b.Loop on Go 1.24+, memory tracking with -benchmem, table-driven sub-benchmarks, sink discipline against dead-code elimination), running them right (output format, flags, -count for significance), comparing with benchstat (confidence intervals, p-values, hardware context lines, what to strip from commit messages), profiling from benchmark runs (CPU/mem profiles, execution trace), and guarding CI against regressions (benchdiff, cob, gobenchdata, noisy-neighbor mitigation, self-hosted runner tuning). A companion to golang-troubleshooting and golang-performance in the same repo — it does the measuring, the others do the fixing. Expects a Go toolchain plus benchstat (installed via go install golang.org/x/perf/cmd/benchstat@latest). Discovered via skills.sh. Honest note: it is statistically rigorous by design — never trust a single run, and a benchstat delta straddling the Go 1.26→1.27 toolchain boundary measures the toolchain (allocator changes) not your code; cloud CI benchmarks wobble 5–10% even on quiet machines. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/samber-golang-benchmark
- Fiche en français: https://theskillharbor.com/fr/products/samber-golang-benchmark
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/samber/cc-skills-golang/blob/main/skills/golang-benchmark/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
