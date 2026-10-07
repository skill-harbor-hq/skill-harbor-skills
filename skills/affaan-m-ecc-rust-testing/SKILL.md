<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-rust-testing
description: "TDD in Rust: unit, integration, async, and property-based tests with mockall, proptest, and..."
---

# Rust Testing

Curated by Skill Harbor: a comprehensive TDD workflow for Rust, from the red-green-refactor cycle down to concrete tooling. Covers unit tests in #[cfg(test)] modules, integration tests under tests/ (each file its own test binary), async tests with tokio (including timeout handling), parameterized tests and fixtures with rstest, property-based testing with proptest (roundtrip properties, custom strategies like generated emails), trait mocking with mockall, executable doc tests, Criterion benchmarks with HTML reports, and coverage with cargo-llvm-cov (sensible targets: 100% for critical business logic, 90%+ for public API, 80%+ general, with a --fail-under-lines gate). Includes a GitHub Actions CI template (fmt check, clippy with denied warnings, test run, coverage gate) and a best-practices list: test behavior not implementation, prefer assert_eq! for better messages, keep tests independent with no shared mutable state, fix flaky tests instead of ignoring them, never sleep() in tests. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; assumes a Rust toolchain (cargo) with the above crates as dev-dependencies. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-rust-testing
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-rust-testing
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/rust-testing/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
