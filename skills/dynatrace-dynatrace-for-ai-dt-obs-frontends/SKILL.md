<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: dynatrace-dynatrace-for-ai-dt-obs-frontends
description: "Monitor web and mobile frontends with Real User Monitoring in DQL — Core Web Vitals metrics, user..."
---

# Frontend observability with Dynatrace RUM: Core Web Vitals, sessions, errors

💳 Paid platform required — Dynatrace is a paid service: you need a Dynatrace account with RUM (Real User Monitoring) enabled for this skill to be usable. Curated by Skill Harbor — @dynatrace's skill for frontend observability on the latest Dynatrace (RUM, not RUM Classic): three data sources for three questions — `dt.frontend.*` timeseries metrics for trends, dashboards and alerting; `user.events` for root cause (page views, requests, clicks, errors); `user.sessions` for journeys, bounce rate and session aggregates. The drill-down pattern: identify the frontend (group by `frontend.name`), find the affected page (`page.name`) or view (`view.name`), then narrow with dimensions (browser, app version, geography, device type, synthetic vs real traffic). Includes the key metric names (LCP, INP, CLS, FID, TTFB, error counts, request/user-action volume), the Core Web Vitals threshold quick reference (LCP good < 2.5 s, INP good < 200 ms, CLS good < 0.1), sensitive-field handling (`client.ip`, `user.identifier` are hidden by default — a fieldset policy grant is needed), and a workflow-to-reference map (web-vitals, user-sessions, error-tracking, mobile-monitoring, frontend-backend-linking, CSP violations, slow-page-load playbook, troubleshooting). Honest caveats: RUM only — synthetic monitoring, backend services, logs and problems are separate skills (dt-obs-synthetic, dt-obs-services, dt-obs-logs, dt-obs-problems) not bundled here; the detailed reference files load on demand....

- Listing: https://theskillharbor.com/products/dynatrace-dynatrace-for-ai-dt-obs-frontends
- Fiche en français: https://theskillharbor.com/fr/products/dynatrace-dynatrace-for-ai-dt-obs-frontends
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/dynatrace/dynatrace-for-ai/blob/main/skills/dt-obs-frontends/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
