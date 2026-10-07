<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-rails-patterns
description: "Rails 7.1+ and 8.x patterns: skinny controllers, service objects, Hotwire, and the Solid stack."
---

# Rails Patterns

Curated by Skill Harbor: the community-converged patterns for Ruby on Rails apps that stay maintainable past the 50-model mark (Rails 7.1+ and 8.x). Covers the directory contract (services/, forms/, queries/, jobs/ and where each belongs, with no casual new directories), skinny controllers that delegate to service objects returning Result objects (namespaced by domain, single-purpose, transactional multi-record writes), form objects for multi-model forms, composable query objects for complex ActiveRecord queries, background jobs (pass IDs not records, idempotent perform, explicit retry_on/discard_on), ViewComponent over partials for testable view logic, Hotwire as the default frontend (Turbo Frames for partial updates, Turbo Streams for server-driven updates, Stimulus for small behaviors), and the Rails 8 Solid stack (Solid Queue, Solid Cache, Solid Cable backed by the database instead of Redis, Kamal for deploys). Includes bad-vs-good code examples throughout, N+1 prevention with includes and strict_loading, counter caches, and a sharp anti-pattern list (god controllers, fat models, callback chains, nested attributes for complex forms, default scopes, reaching for a JS framework before Hotwire). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; Rails-oriented throughout, you need a Rails codebase to apply it. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-rails-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-rails-patterns
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/rails-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
