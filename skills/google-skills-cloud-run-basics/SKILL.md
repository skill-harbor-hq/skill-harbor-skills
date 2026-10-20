<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-skills-cloud-run-basics
description: "Manage Cloud Run services, jobs and worker pools — deploy from source or image, IAM, networking..."
---

# Cloud Run basics: deploy services, jobs and worker pools

Honest caveats: requires a Google Cloud project with billing enabled and the gcloud CLI — the free tier covers generous quotas (2M requests/month); deployment-failure guidance is built in (read logs immediately on crash-on-boot, switch to buildpacks for native-dependency errors); docs move fast, so the skill points at live reference docs for anything beyond its scope. Discovered via skills.sh. Note on attribution: every direct terminal `gcloud` invocation carries an inline usage-attribution tag, and direct API or MCP calls carry the same tag in their User-Agent — keep that prefix out of generated scripts, Terraform and user-facing code as the skill instructs; the tag identifies only the skill and its version, carries no user data, and a user opt-out is documented in the skill. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/google-skills-cloud-run-basics
- Fiche en français: https://theskillharbor.com/fr/products/google-skills-cloud-run-basics
- Category: Cloud
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google/skills/blob/main/skills/cloud/cloud-run-basics/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
