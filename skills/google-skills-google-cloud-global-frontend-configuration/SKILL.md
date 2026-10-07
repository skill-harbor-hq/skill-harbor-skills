<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-skills-google-cloud-global-frontend-configuration
description: "Guided 6-step discovery to design and deploy a global external ALB with Cloud CDN caching, Cloud..."
---

# Design and deploy global external Application Load Balancers on Google Cloud

Curated by Skill Harbor — Google's official skill for designing and deploying Google Cloud global external Application Load Balancers: a 6-step discovery process. Step 1, project and protocol/cert basics. Step 2, sequential origin definition — Cloud Storage, Compute Engine MIGs, GKE clusters, Cloud Run services or external IPs/FQDNs — classified by workload type (static assets, cacheable API, uncacheable/transactional, dynamic SSR), then routing rules and CDN logging. Step 3, traffic management and Service Extensions (WASM plugins/callouts). Step 4, workload-mapped Cloud CDN caching (TTL, cache keys, compression, negative caching presets per workload). Step 5, Cloud Armor WAF — rate limiting and OWASP rules calibrated per workload (strict thresholds for login/checkout endpoints). Step 6, review, then emit production-grade Terraform HCL or gcloud CLI scripts, deployed via Infrastructure Manager or bash — with drift detection afterwards. Details stay progressively disclosed; recommended best-practice configs first, advanced knobs only on request. Honest caveats: methodology plus generated IaC — deploying what it designs provisions REAL Google Cloud infrastructure (billing-enabled account required, real cloud costs; deploying anything costs real money); gcloud availability assumed for automated discovery and actuation — without it the skill degrades gracefully to design-only mode. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use....

- Listing: https://theskillharbor.com/products/google-skills-google-cloud-global-frontend-configuration
- Fiche en français: https://theskillharbor.com/fr/products/google-skills-google-cloud-global-frontend-configuration
- Category: Cloud
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google/skills/blob/main/skills/cloud/google-cloud-global-frontend-configuration/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
