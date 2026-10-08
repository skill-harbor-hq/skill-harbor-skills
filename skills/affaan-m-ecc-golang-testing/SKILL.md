<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-golang-testing
description: "Idiomatic Go testing with Muse: table-driven tests, subtests, TDD red-green-refactor, benchmarks..."
---

# Go Testing Patterns

Curated by Skill Harbor: a comprehensive Go testing playbook that teaches Muse the idiomatic way to test Go. The TDD workflow is spelled out step by step: write the failing test first, watch it fail, write minimal code, refactor, with a full worked example of a calculator Add function. Table-driven tests get the canonical treatment: a slice of structs with name, inputs, and expected output, run through t.Run subtests, including error-case variants. Subtests, test helpers with t.Helper, and parallel tests are covered. Benchmarks follow with the b.N loop pattern and memory allocation checks. Fuzzing covers the Fuzz target signature, seed corpus, and how to keep failing inputs. Coverage guidance targets meaningful thresholds rather than chasing numbers, plus the race detector for concurrency bugs. Test doubles, table tests for HTTP handlers with httptest, and golden files for complex output round out the set. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: coverage percentages are a signal, not proof of correctness; fuzzing needs a real corpus to find anything. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-golang-testing
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-golang-testing
- Category: Go
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/golang-testing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
