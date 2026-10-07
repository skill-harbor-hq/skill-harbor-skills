<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-deployment-patterns
description: "Rolling, blue-green, and canary strategies plus CI/CD pipelines, health checks, and production..."
---

# Deployment Patterns

Curated by Skill Harbor: production deployment workflows and CI/CD best practices for web applications. Walks through the three core rollout strategies with their trade-offs: rolling deployments (zero downtime, but two versions coexist so changes must stay backward compatible), blue-green (instant rollback by switching traffic, at the cost of double infrastructure during cutover), and canary releases, plus the supporting machinery that makes them safe: health checks and readiness probes, environment-specific configuration, Docker containerization, and a production readiness checklist to run before every release. Written to be used at two moments: when setting up a pipeline from scratch, and as a pre-release sanity check when the stakes are high. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: strategy guidance, not a turnkey pipeline; you still adapt it to your platform (Kubernetes, VPS, PaaS) and your team's tolerance for risk. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-deployment-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-deployment-patterns
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/deployment-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
