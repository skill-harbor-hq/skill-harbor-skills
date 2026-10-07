<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: samber-golang-testing
description: "Production-ready Go tests: table-driven, parallel, leak-free"
---

# Golang Testing Best Practices Skill for Muse

A senior Go engineer persona for writing production-ready tests, with four working modes: write (scaffold with gotests, then enrich with edge cases), review (audit a PR's test diff), audit (fan out three parallel sub-agents over unit quality, integration isolation, and goroutine/race issues), and debug (reproduce reliably, isolate the assertion, trace the root cause). The best-practices core is opinionated and concrete: table-driven tests with named subtests, integration tests behind build tags, no order dependence, t.Parallel() for independent tests, assert observable behavior not implementation details, goleak in TestMain for goroutine leaks, and coverage treated as a gap finder, not a target. Particularly valuable: the pitfall it documents — testify assert scope leaking into subtests, where every subtest reports PASS while the parent fails — plus modern Go testing idioms like testing/synctest for deterministic concurrency tests (Go 1.25+) and t.ArtifactDir for test outputs (Go 1.26+). Ships a dense go test quick-reference (run filters, -race, -cover, -bench, -fuzz, build tags) and deep-dive references for HTTP testing, mocking, fixtures, benchmarks, and integration testing in the repo. Discovered via skills.sh. Honest note: designed for Claude Code/Codex-style harnesses — it speaks in ultrathink/ultracode idioms you can ignore elsewhere — and it assumes the Go toolchain plus gotests on your machine; the referenced deep-dives live in the repo, so fetch the whole skill...

- Listing: https://theskillharbor.com/products/samber-golang-testing
- Fiche en français: https://theskillharbor.com/fr/products/samber-golang-testing
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/samber/cc-skills-golang/blob/main/skills/golang-testing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
