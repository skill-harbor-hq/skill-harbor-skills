<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: release-gate
description: "Pre-merge, pre-install verification with a GO / NO-GO verdict."
---

# Release Gate

A Muse agent skill that runs the checks that matter before you merge or install anything: a full verification pass (tests, build, lint) with a hard GO / NO-GO verdict, plus a lightweight fast-gate mode for quick pre-install decisions. GO never means "flawless" — it means the riskier checks ran and the failures are none or acceptable; NO-GO always names the cause and what to do next. A warning gate exists for judgment calls it can't resolve alone. No account, no API key, no network needed.

- Listing: https://theskillharbor.com/products/release-gate
- Fiche en français: https://theskillharbor.com/fr/products/release-gate
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Israelmusondaayliffe/muse-skills/tree/main/skills/release-gate

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
