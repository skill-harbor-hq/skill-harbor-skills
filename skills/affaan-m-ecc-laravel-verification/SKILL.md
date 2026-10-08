<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-laravel-verification
description: "Pre-merge and pre-deploy verification for Laravel with Muse: environment checks, Pint and PHPStan..."
---

# Laravel Verification Loop

Curated by Skill Harbor: a phased verification loop that makes Muse walk a Laravel project from environment checks to deployment readiness before every pull request or deploy. Phase 1 verifies PHP, Composer and Artisan versions plus the .env (APP_DEBUG=false, APP_ENV matching the target); Composer validation and autoload come next and gate everything else. Phase 2 runs Pint formatting checks and PHPStan static analysis, which must be clean before tests. Phase 3 runs the test suite with coverage targets for CI. Phase 4 audits dependencies with composer audit. Phase 5 reviews database safety with migrate --pretend and migrate:status, destructive-migration review, and rollback checks. Phase 6 warms the production caches (config, routes, views) and verifies storage writability, and Phase 7 closes with queue and scheduler gates, including a safe staging-only queue healthcheck that dispatches a no-op job and processes it once. Each phase builds on the last, so a failure early stops the loop before it wastes time on later gates. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the loop assumes your project actually has Pint, PHPStan and tests configured; it reports, it does not fix; the queue healthcheck is staging-only, never run it on production. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-laravel-verification
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-laravel-verification
- Category: Laravel
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/laravel-verification/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
