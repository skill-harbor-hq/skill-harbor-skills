<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-integration-connectivity-generate
description: "Generate Salesforce integration plumbing — credentials, REST/SOAP callouts, Platform Events, CDC —..."
---

# Salesforce integration connectivity: Named Credentials, External Services, callouts, events and CDC

Curated by Skill Harbor — @forcedotcom's expert skill for Salesforce integration architecture and runtime plumbing. It covers setting up Named Credentials and External Credentials, registering External Services from OpenAPI specs, outbound REST/SOAP callout patterns, and event-driven design with Platform Events and Change Data Capture (with clear routing rules for when to delegate to the sibling skills for Connected App setup, Apex-only logic, metadata deploy or CDC channel config). The workflow: choose the integration pattern from a decision table, pick a secure auth model (runtime-managed, never hardcoded secrets), generate from XML/Apex asset templates (credentials, callouts, platform events, CDC handlers, SOAP, endpoint security), validate operational safety (timeouts, retries, async strategy, observability), and score the result on a 120-point rubric across six categories (security, error handling, bulkification, architecture, best practices, documentation). Honest caveats: Salesforce-specific — useless outside the Salesforce platform; requires the `sf` CLI plus jq, npm and python3; the skill lives inside a plugin pack and expects its bundled assets and reference guides. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-integration-connectivity-generate
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-integration-connectivity-generate
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/plugins/builder/integration/skills/integration-connectivity-generate/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
