<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-skills-google-ads-api-quickstart
description: "Go from zero to a first working Google Ads API call — developer token, OAuth, 6 client libraries or..."
---

# Google Ads API quickstart

Curated by Skill Harbor — @google's own zero-to-first-call guide for the Google Ads API: obtain the five authentication parameters (developer token from the API Center of a Manager account, OAuth client ID/secret with a Desktop App consent screen in Testing mode plus registered test users, refresh token via the gcloud device flow, client customer ID, login customer ID), then choose an integration track — official client libraries (Python, Java, .NET, PHP, Ruby, Perl) or direct REST — with a hard discipline the skill enforces at run time: **never hardcode the API or runtime versions**; resolve the latest stable major version from the release notes and the language minimums from the supported-versions page at the start of execution (with documented offline fallbacks), outputting a version anchor as the first line of the response. Includes static-only troubleshooting for the two classic setup failures — `USER_PERMISSION_DENIED` (missing login_customer_id in a manager hierarchy) and `DEVELOPER_TOKEN_NOT_APPROVED` (pending token restricted to test accounts, with the three production access levels named) — and hands off AI-assistant/MCP use cases to the dedicated `google-ads-api-mcp-setup` skill. Honest caveats: requires a Google Ads Manager account and developer token (a **pending token works on test accounts only**); the API itself has no per-call fee but ad spend is separate; dynamic version resolution means the agent may need live web access at run time. Apache-2.0 licensed....

- Listing: https://theskillharbor.com/products/google-skills-google-ads-api-quickstart
- Fiche en français: https://theskillharbor.com/fr/products/google-skills-google-ads-api-quickstart
- Category: Marketing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google/skills/blob/main/skills/ads/google-ads-api-quickstart/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
