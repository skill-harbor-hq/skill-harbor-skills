<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: martinholovsky-claude-skills-generator-rust
description: "Ownership/borrowing, Tokio async, unsafe/FFI boundaries, Tauri commands and IPC, zero-cost..."
---

# Rust Systems Programming — memory-safe Tauri backends with TDD and security patterns

Curated by Skill Harbor — @martinholovsky's rust: a Rust systems programming skill specializing in Tauri desktop application backends, with TDD-first discipline. Covers ownership/borrowing/lifetimes, async Rust with Tokio, FFI and unsafe-code safety, the Tauri command system and IPC, performance patterns (zero-copy, iterators, memory pooling, spawn_blocking), and a security standards section: CVE mitigations (CVE-2024-24576 / CVE-2024-43402 command injection — upgrade Rust), input validation at boundaries (validator crate, newtypes), path-traversal prevention (dunce canonicalization with containment checks), safe command execution via allowlists (no shell with user input), secrets from env rather than hardcoded, and cargo-audit in CI. Honest caveats: the skill self-declares risk_level MEDIUM — unsafe blocks, FFI and command execution are the subject matter, and every example is defensive (allowlists, validation, SAFETY docs), not offensive; it points to bundled references/ files (security examples, advanced patterns) that ship with the repo. The skill's frontmatter states no license; the catalog manifest records Unlicense — manifest takes precedence. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/martinholovsky-claude-skills-generator-rust
- Fiche en français: https://theskillharbor.com/fr/products/martinholovsky-claude-skills-generator-rust
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/martinholovsky/claude-skills-generator/blob/main/skills/rust/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
