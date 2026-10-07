<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-skills-agent-platform-deploy
description: "Deploy Model Garden open models (or 1P tuned models) to Agent Platform endpoints with tiered..."
---

# Deploy open models to Agent Platform: cost-checked, confirmation-gated

Curated by Skill Harbor — Google's official skill for deploying open models and custom weights from Model Garden to Agent Platform endpoints: discover deployable models via `gcloud ai model-garden models list`, check supported machine types and accelerators per model, then deploy with the `:deploy` API. Its defining feature is a strict safety-and-confirmation tier system: read-only actions (list, describe) run freely; mutating actions (deploy, undeploy) require an explicit dry-run confirmation card showing the model ID, project, region, machine type, endpoint display name and — critically — an estimated hourly cost that must be computed (via the bundled calculate_cost.py script or the published pricing page, never invented); destructive actions (delete) require typed confirmation. Includes status checks (single describe per turn — no sleep loops), test-prediction verification via the endpoint's dedicated DNS, undeploy/cleanup guidance, a 1P tuned-model cross-region copy guide, quota-troubleshooting playbooks, and a cost-pushback/region-failover renegotiation flow. Honest caveats: deploying provisions REAL Google Cloud compute — a Google Cloud account with billing enabled is required and every deploy incurs real hourly costs (undeploy when done or charges continue); the skill never names model versions from memory — it always re-queries the live catalog. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/google-skills-agent-platform-deploy
- Fiche en français: https://theskillharbor.com/fr/products/google-skills-agent-platform-deploy
- Category: Cloud
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google/skills/blob/main/skills/cloud/agent-platform-deploy/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
