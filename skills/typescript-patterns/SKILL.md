<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: typescript-patterns
description: "TypeScript patterns for strict, type-safe, maintainable code."
---

# typescript-patterns

typescript-patterns starts from one guiding principle: push the type system to do real work instead of fighting it, since the compiler is most useful when it can prove a program's shape. It is the "how"; for the "what" and "when" (the decisions about which pattern to reach for), it points to the TypeScript rules in the same repository. Strict mode is the baseline: strict true is not optional in a healthy codebase, and if a codebase cannot compile under strict, that is a migration task, not an excuse to leave the flag off, with a strict, discriminating baseline config including noUncheckedIndexedAccess, exactOptionalPropertyTypes, noImplicitOverride, and verbatimModuleSyntax. Any is treated as a bug, not a tool: prefer unknown and narrow it, with explicit loosening and a comment when a fallback is truly needed. Public APIs get explicit types while locals get inference; interfaces are for object shapes that may be extended or implemented, types for unions, intersections, tuples, mapped types, and utility types; discriminated unions are the default state machine, with exhaustive checking as a free compiler feature; brands add nominal safety where structure is not enough; generics model caller-dependent types; and functions with more than a couple of knobs take a single options object. Narrowing and runtime safety rules cover validating at the boundary and trusting inside, type predicates and assertion functions, and readonly by default. Error handling covers failing at the...

- Listing: https://theskillharbor.com/products/typescript-patterns
- Fiche en français: https://theskillharbor.com/fr/products/typescript-patterns
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
