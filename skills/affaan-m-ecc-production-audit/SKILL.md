<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-production-audit
description: "Ship-or-block audits for Muse: local-evidence production readiness reviews with risk lenses, scored..."
---

# Production Audit

Curated by Skill Harbor: a production readiness audit that answers "is this ready to ship?" from local evidence, without uploading your repo to an external audit service. Builds the audit from evidence you authorize: release surface, recent changes and branch state, runtime and auth and payment and deployment boundaries in the repo, CI and tests and migrations and rollback paths. Applies five risk lenses: security and auth (route separation, server-side enforcement, secrets out of bundles, rate limits, prompt injection defenses), data integrity (forward-clean migrations with rollback plans, staged backfills, idempotent retries), payments and webhooks (signature verification, idempotent fulfillment, replay and duplicate handling, test versus live credentials), operations (clean-checkout startup, validated env vars, health checks, documented deploy and rollback paths, useful logs without secret leaks), and user experience (launch-critical paths on desktop and mobile, loading and error states, recovery paths). Scores 0-100 in four bands (Blocked, Risky, Launchable With Caveats, Strong) with hard caps: auth missing on sensitive data or non-idempotent payment webhooks or exposed secrets or no rollback path caps the score at 69, non-green CI caps it at 84. Output leads with one sentence (score, band, top risks), then blockers, high-value fixes, evidence checked, evidence missing, and one next action. Use before a launch, after a merge, or when asked what breaks in prod. By...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-production-audit
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-production-audit
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/production-audit/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
