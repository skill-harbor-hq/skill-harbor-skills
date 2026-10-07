<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: actionbook-rust-skills-coding-guidelines
description: "50 Rust-specific style rules — naming, formatting, clippy, error handling, memory, concurrency..."
---

# Rust coding guidelines: 50 core rules for idiomatic Rust

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @actionbook's 50-rule Rust style guide, built from the community rust-coding-guidelines document — Rust-specific naming rules (no `get_` prefix, `as_`/`to_`/`into_` conversion conventions, `iter()`/`iter_mut()`/`into_iter()`), error-handling discipline (propagate with `?`, prefer `expect()` over `unwrap()`), memory and lifetime habits, concurrency rules (atomics for primitives, explicit lock ordering), async guidance (async is for I/O, never hold locks across await), macro discipline, and a deprecated→better table (`lazy_static!` → `OnceLock`, `try!` → `?`, `failure` → `thiserror`/`anyhow`). Honest caveats: methodology only, no tooling — the agent needs a Rust project to apply it to; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/actionbook-rust-skills-coding-guidelines
- Fiche en français: https://theskillharbor.com/fr/products/actionbook-rust-skills-coding-guidelines
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/actionbook/rust-skills/blob/main/skills/coding-guidelines/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
