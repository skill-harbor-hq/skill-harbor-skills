<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: seo-drift
description: "A specialised sub-skill of the claude-seo family (orchestrated by the seo skill, a separate..."
---

# SEO Drift

A specialised sub-skill of the claude-seo family (orchestrated by the seo skill, a separate listing): 'Git for SEO' drift monitoring that snapshots a page's SEO-critical elements, diffs them against stored baselines with 17 rules in 3 severities, and tracks history. At use, through the family's SSRF-protected tools (outside this folder), it fetches the monitored page, optionally calls PageSpeed for Core Web Vitals, and writes its baselines to a local SQLite database at ~/.cache/claude-seo/drift/baselines.db. Its text states fetched content is untrusted data, never instructions, and contains no 'Built by agricidaniel' footer instruction.

Part of the Claude SEO family. Installing this listing alone copies only this skill's folder, without the shared launcher, the shared scripts or the sibling skills. For the full family install, its prerequisites and its Muse limits, see the guide: How to Install the Claude SEO Family - /guides/how-to-install-the-claude-seo-family/ - and the other core listings: seo, seo-agentic, seo-audit, seo-backlinks, seo-cluster, seo-competitor-pages, seo-content, seo-content-brief, seo-drift, seo-ecommerce, seo-flow, seo-geo, seo-google, seo-hreflang, seo-image-gen, seo-images, seo-local, seo-maps, seo-page, seo-plan, seo-programmatic, seo-schema, seo-sitemap, seo-sxo, seo-technical.

- Listing: https://theskillharbor.com/products/seo-drift
- Fiche en français: https://theskillharbor.com/fr/products/seo-drift
- Category: SEO
- Price: Free
- Verification: unverified
- Source repo: https://github.com/AgriciDaniel/claude-seo/blob/main/skills/seo-drift/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
