<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-django-celery
description: "Django + Celery async task patterns: broker setup, task design, Beat scheduling, retries, canvas..."
---

# Django Celery

Curated by Skill Harbor: a patterns skill for production-grade background task processing in Django with Celery (Redis or RabbitMQ as broker). It covers project setup and broker configuration, task design that stays idempotent and debuggable, Celery Beat for cron-like periodic scheduling, retry policies with backoff for flaky work, canvas workflows (chains, groups, chords) for multi-step pipelines, monitoring task health and queue backlogs, and testing Celery tasks without flaky suites. Offload the slow stuff (emails, PDF generation, API calls) from the request cycle with patterns that survive real production load. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; requires a running broker (Redis or RabbitMQ) for anything beyond reading; assumes a working Django project. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-django-celery
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-django-celery
- Category: Django
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/django-celery/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
