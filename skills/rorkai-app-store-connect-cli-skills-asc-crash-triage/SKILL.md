<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rorkai-app-store-connect-cli-skills-asc-crash-triage
description: "Fetch, analyze and summarize TestFlight crash reports, beta feedback and perf diagnostics via the..."
---

# App Store Connect crash triage: TestFlight crashes, beta feedback and performance diagnostics

Curated by Skill Harbor — @rorkai's triage skill for App Store Connect: fetch, analyze and summarize TestFlight crash reports, beta tester feedback and performance diagnostics (app hangs, disk writes, launch diagnostics) through the `asc` CLI. The workflow resolves the app ID, lists recent crashes (filterable by build, device model, OS version), pulls beta feedback with screenshots, and reads performance diagnostic signatures — then presents a human-readable summary organized by severity and frequency (total count, top crash signatures, affected builds, device & OS breakdown, timeline). Honest caveats: requires the `asc` CLI plus App Store Connect API access; crash data from App Store Connect can lag 24–48 hours. MIT-licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/rorkai-app-store-connect-cli-skills-asc-crash-triage
- Fiche en français: https://theskillharbor.com/fr/products/rorkai-app-store-connect-cli-skills-asc-crash-triage
- Category: Mobile
- Price: Free
- Verification: unverified
- Source repo: https://github.com/rorkai/app-store-connect-cli-skills/blob/main/skills/asc-crash-triage/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
