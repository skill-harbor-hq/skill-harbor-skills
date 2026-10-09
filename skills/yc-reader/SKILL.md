<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: yc-reader
description: "Look up Y Combinator companies and batches from the public yc-oss dataset: profiles, batch rosters..."
---

# YC Reader

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. YC portfolio data describes startups, most of them private, illiquid and likely to fail: a hiring badge or a top-company label is a growth signal in a dataset, not an investment case, there is a real risk of loss in any venture decision taken from directory data, and no output here is a promise of return. Curated by Skill Harbor: the Y Combinator reader of himself65/finance-skills. Use it for startup and venture research that draws on YC data: company profiles, batch rosters (winter, spring, summer and fall batches back to 2005), companies by industry or by tag, the top companies list, the companies currently hiring (roughly 1,400 in the dataset the skill describes, a growth signal worth tracking), non-profits, founder-diversity lists, and overall YC statistics. The data comes from the yc-oss/api project, an unofficial open-source API that indexes all publicly launched YC companies from YC's own search index and refreshes daily as static JSON files, so it is read-only by construction, with no write operations at all and no authentication: the skill fetches endpoints with curl and filters them client-side with jq. Results are summarized rather than dumped: name, one-liner, batch, team size, status, hiring status and website per company, and aggregate counts and distributions for research questions. From the himself65/finance-skills repository (MIT). Honest caveats: this is an...

- Listing: https://theskillharbor.com/products/yc-reader
- Fiche en français: https://theskillharbor.com/fr/products/yc-reader
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/himself65/finance-skills/blob/main/plugins/social-readers/skills/yc-reader/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
