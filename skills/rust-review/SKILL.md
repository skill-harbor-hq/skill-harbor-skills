<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rust-review
description: "Prioritized Rust code reviews where every finding cites its rule and fix."
---

# rust-review

rust-review reviews exactly what the user points at: a file, a module, a crate, a diff, or a pull request. For a diff, it reviews the changed lines and anything they break, not the whole file. It states whether the code is library or application code, plus the edition and minimum supported Rust version from Cargo.toml, so it never recommends features the project cannot use. It works through correctness and soundness first (unsafe blocks without a SAFETY comment, reachable panics, broken trait contracts, lock hazards, Bevy ECS bugs, failing destructors), then error handling, API design for libraries, idiom and clarity, and documentation and tests. The output is a review, not a rewrite: the reader decides what to fix, and code is rewritten only when the user asks for it. Findings are grouped when they repeat, deliberate quirks are noted under Consider with their trade-off rather than marked Must fix, and a "What's already good" section is required. Limits as written: if the Rust tools are not available, the skill says so in the report and reviews by reading. It pairs with the rust-best-practices skill, which covers writing new code. Credit: created by morganlinton, in the BeautifulRust repository. Source: https://github.com/morganlinton/BeautifulRust, file skills/rust-review/SKILL.md.

- Listing: https://theskillharbor.com/products/rust-review
- Fiche en français: https://theskillharbor.com/fr/products/rust-review
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
