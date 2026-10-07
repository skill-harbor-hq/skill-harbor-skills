<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-skills-gcloud
description: "Mandatory syntax validation via gcloud help, data-reduction rules, and a denylist for..."
---

# gcloud CLI safety guardrails for AI agents (official Google skill)

Curated by Skill Harbor — @google's official safety harness for letting AI agents touch the gcloud CLI without hallucinating flags or deleting production: a mandatory pre-condition that treats all prior knowledge of gcloud syntax as stale, so every leaf-level command must first be validated with `gcloud help <leaf_command>` (web search is explicitly forbidden as a syntax source), plus data-reduction rules (never a list without --limit/--filter/--format), execution constraints (single commands, no pipes or chaining, --quiet always, explicit --project and location flags), dry-run discipline, and a denylist blocking autonomous IAM, billing, KMS, org and delete operations. Apache-2.0 licensed. Honest notes: this is a rulebook, not code — it makes your agent careful, not magical; and you still need the gcloud CLI and a Google Cloud project (a paid platform — check pricing) to use it. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/google-skills-gcloud
- Fiche en français: https://theskillharbor.com/fr/products/google-skills-gcloud
- Category: Cloud
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google/skills/blob/main/plugins/cloud/google-cloud-developer/skills/gcloud/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
