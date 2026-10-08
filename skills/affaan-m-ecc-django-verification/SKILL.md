<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-django-verification
description: "Twelve-phase Django verification with Muse: mypy, ruff and black, migration safety, pytest coverage..."
---

# Django Verification Loop

Curated by Skill Harbor: a twelve-phase verification loop that makes Muse produce a pass/fail report for a Django project before any pull request or deploy. Phase 1 checks the Python environment and required variables; Phase 2 runs mypy, ruff, black and isort plus manage.py check --deploy for Django-specific issues. Phase 3 validates migration safety (unapplied migrations, conflicts, model changes without migrations). Phase 4 runs pytest with coverage targets per component (models 90%+, services 90%+, overall 80%+). Phase 5 scans security with pip-audit, safety, bandit and gitleaks, and confirms DEBUG is off. Phases 6 through 11 cover management commands, static assets, performance (N+1 queries, missing indexes), configuration review (SECRET_KEY, ALLOWED_HOSTS, HTTPS, HSTS), logging, and API documentation. Phase 12 reviews the diff itself for debug statements, TODOs, hardcoded secrets and missing migrations, and ends with a pre-deployment checklist plus a GitHub Actions template that runs the whole loop in CI. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: automated verification catches common issues but does not replace manual code review or staging tests; coverage targets are defaults to tune per project; the skill reports findings, it does not apply fixes. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-django-verification
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-django-verification
- Category: Django
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/django-verification/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
