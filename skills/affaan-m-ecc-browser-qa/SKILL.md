<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-browser-qa
description: "Automated post-deploy UI verification with a browser automation MCP: console-error and Core Web..."
---

# Browser QA

Curated by Skill Harbor: an automated browser QA skill that verifies your deployed frontend the way a careful tester would, before you ship. Driven by a browser automation MCP (claude-in-chrome, Playwright, or Puppeteer), it runs four phases: a smoke test (console errors, 4xx/5xx network requests, above-the-fold screenshots, Core Web Vitals thresholds), an interaction test (every nav link, forms with valid and invalid data, auth flows, critical user journeys), a visual regression pass (screenshots at 375px, 768px, and 1440px compared against committed baselines, no baseline means INCONCLUSIVE never a silent pass), and an accessibility audit (axe-core, WCAG 2.2 AA, keyboard navigation, screen reader landmarks), ending in an explicit SHIP or DO-NOT-SHIP verdict. Safety is built in: read-only by default, mutating journeys only against staging with explicit opt-in, seeded test credentials never production logins, and credentials redacted from screenshots. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: requires a browser automation MCP configured (claude-in-chrome, Playwright, or Puppeteer); axe-core covers roughly a third of WCAG, the rest needs human judgment; never run mutating journeys against production. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-browser-qa
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-browser-qa
- Category: Testing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/browser-qa/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
