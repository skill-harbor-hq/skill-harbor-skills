<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-skills-gke-golden-path
description: "@google's opinionated GKE Autopilot configuration — production defaults, Day-0 vs Day-1 decisions..."
---

# GKE golden path: production-ready cluster defaults and readiness checklists

Honest caveats: guidance and defaults only — it does not provision or change cloud resources itself; product defaults may drift from Google Cloud docs; requires GCP access for anything real. Apache-2.0 licensed. Updated October 20, 2026 (version 1.1.1): before any direct terminal command, the skill now points to references/attribution.md — every direct terminal `gcloud` invocation carries an inline usage-attribution tag (`agent-skills/1.0 (skill:gke-golden-path)`), and direct REST/MCP calls add it to the User-Agent — keep that prefix out of generated scripts, Terraform and user-facing code as the skill instructs; the tag identifies only the skill and its version, carries no user data, and a user opt-out is documented. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/google-skills-gke-golden-path
- Fiche en français: https://theskillharbor.com/fr/products/google-skills-gke-golden-path
- Category: Cloud
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google/skills/blob/main/skills/cloud/gke-golden-path/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
