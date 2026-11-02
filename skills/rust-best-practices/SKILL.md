<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rust-best-practices
description: "Write idiomatic, robust, maintainable Rust."
---

# rust-best-practices

The mindset is: write Rust-shaped code, not a one-to-one port of C++, Java, C# or Python; make invalid states unrepresentable, with enums instead of bool flags, newtypes for units and IDs, and fallible constructors that validate once; treat application code and library code differently, favoring simplicity in applications and strict API rules in libraries; and let the tools do the work, with rustfmt owning formatting, clippy owning idiom checks, and the compiler owning memory safety.

Before handing back code, run cargo fmt, cargo clippy with all targets and all features and warnings denied, cargo test, and cargo doc without dependencies for libraries, and fix everything they report. Fix a lint rather than silencing it, using expect on the narrowest item when a lint is genuinely wrong, and allow only in generated code or macro output. Never put deny(warnings) in source: enforce warnings as errors in CI instead. Configure lints once in Cargo.toml, not with scattered crate attributes.

The guide then covers ownership and borrowing, preferring unique ownership and the most general borrowed type, types and API design, naming, newtypes, standard trait derives, constructors and builders, visibility and evolution, traits and generics, refactoring someone else's code, errors and panics, everyday idioms, concurrency and async, unsafe and FFI, crates, modules and dependencies, documentation and comments, tests, and performance in order. Each section states its rule and its reason...

- Listing: https://theskillharbor.com/products/rust-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/rust-best-practices
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/morganlinton/BeautifulRust

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
