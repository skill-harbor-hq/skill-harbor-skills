<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: dart-lang-skills-dart-migrate-to-checks-package
description: "Systematically migrate a Dart test suite from legacy package:matcher expect calls to the modern..."
---

# Migrate Dart tests from package:matcher to package:checks

Curated by Skill Harbor — the official Dart team's migration skill for moving a Dart test suite from legacy `package:matcher` (`expect`) to the modern, type-safe `package:checks` assertion library. Walks the agent through the full workflow: dependency setup (add `dev:checks`, incremental vs full migration), a matcher-to-checks mapping table, and — the genuinely valuable part — ten documented syntax differences and pitfalls that a line-for-line translation gets wrong (collection `equals` vs `deepEquals`, `reason` now `because`, `matches` vs `matchesPattern` needing an explicit RegExp, sync vs async `throws`, `bool?` strictness, map `containsKey`, custom expectations via extensions on `Subject<T>`, discovery grep patterns). Includes before/after examples for collections, cascades, property matching and async futures/streams. Honest caveat: written against the checks API as of June 2026 — re-verify syntax if you run a newer package:checks; a line-for-line translation without reading the pitfalls section can introduce false passes. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/dart-lang-skills-dart-migrate-to-checks-package
- Fiche en français: https://theskillharbor.com/fr/products/dart-lang-skills-dart-migrate-to-checks-package
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/dart-lang/skills/blob/main/skills/dart-migrate-to-checks-package/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
