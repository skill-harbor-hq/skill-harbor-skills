<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: seo-audit
description: "FAMILY SYSTEM: this skill is one folder of the claude-seo plugin family; its bundled tools..."
---

# SEO Audit

FAMILY SYSTEM: this skill is one folder of the claude-seo plugin family; its bundled tools, launcher (scripts/claude-seo at the repository root) and sibling seo-* skills live outside this folder, so a standalone copy lacks them. It runs a full-site SEO audit: renders the homepage, crawls up to 500 pages over the network (robots.txt respected), delegates category analyses to the family's sub-agents (separate files), aggregates the weighted SEO Health Score, and writes its artifacts (FULL-AUDIT-REPORT.md, ACTION-PLAN.md, audit-data.json, findings, screenshots) into a <domain>-audit/ folder, with an optional PDF. Optional Google/Matomo/DataForSEO branches use only the user's own configured credentials. Its text states fetched content is untrusted data, never instructions.

- Listing: https://theskillharbor.com/products/seo-audit
- Fiche en français: https://theskillharbor.com/fr/products/seo-audit
- Category: SEO
- Price: Free
- Verification: unverified
- Source repo: https://github.com/AgriciDaniel/claude-seo/blob/main/skills/seo-audit/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
