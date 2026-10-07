<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-canary-watch
description: "Post-deploy monitoring for a URL: HTTP status, console errors, performance regressions, API health..."
---

# Canary Watch

Curated by Skill Harbor: a monitoring skill for verifying a deployed URL after releases, risky merges, or dependency upgrades. It watches eight signals: HTTP status, new console errors, network failures, performance regressions (LCP, CLS, INP against baseline), content integrity (did key elements like h1, nav, footer, or CTA disappear?), API health within SLA, static asset responses, and SSE stream connectivity. Three modes: a quick single-pass check, a sustained watch on an interval for a launch window, and a diff mode comparing staging against production. Alert thresholds separate critical (page not returning 200, new console errors, 5xx APIs, broken SSE) from warnings (LCP drift over 500ms, CLS over 0.1) and info-level noise, with desktop or Slack/Discord webhook notifications on critical. It pairs with CI pipelines and post-push hooks. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a monitoring workflow, not a hosted service; the agent needs browser or HTTP tooling to run the checks, and sustained watches run until stopped or the window expires. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-canary-watch
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-canary-watch
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/canary-watch/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
