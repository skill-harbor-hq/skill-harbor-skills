<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: trailofbits-skills-address-sanitizer
description: "Build and run code under AddressSanitizer to catch buffer overflows, use-after-free and leaks..."
---

# AddressSanitizer: catch memory errors in C, C++ and Rust

Curated by Skill Harbor — a Trail of Bits testing-handbook skill on AddressSanitizer (ASan): how to instrument builds with `-fsanitize=address`, the key `ASAN_OPTIONS` (verbosity, abort-on-error, leak detection), reading crash reports and stack traces, LeakSanitizer usage, and the overhead and platform trade-offs (2–4x slowdown, full support on Linux, limited on macOS, experimental on Windows). Covers tool-specific wiring for libFuzzer, AFL++, cargo-fuzz and honggfuzz (including the 20TB virtual-memory requirement and why you must disable fuzzer memory limits), troubleshooting ("ASan runtime not initialized", false positives, performance cliffs), and the anti-patterns that matter — notably never running ASan-instrumented binaries in production. Honest caveats: fuzzing-target advice — skip for pure safe languages without FFI; CC-BY-SA-4.0 licensed (share-alike applies to reuse of the content). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/trailofbits-skills-address-sanitizer
- Fiche en français: https://theskillharbor.com/fr/products/trailofbits-skills-address-sanitizer
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/trailofbits/skills/blob/main/plugins/testing-handbook-skills/skills/address-sanitizer/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
