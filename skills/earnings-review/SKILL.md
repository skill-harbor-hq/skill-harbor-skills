<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: earnings-review
description: "Event-driven earnings reviews built on primary filings, with quality math and promise tracking..."
---

# Earnings Review

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This review produces evidence only: it never places trades and deliberately never changes thesis state. Curated by Skill Harbor: the earnings discipline of the clawock desk, run manually when a US or Hong Kong holding reports, when a management promise comes due, or before a thesis review that needs primary-source numbers. The source order is not negotiable: SEC filings (10-K, 10-Q, 8-K) or issuer investor relations first for US names, HKEX announcements or issuer IR first for Hong Kong names, with structured datasets (SEC XBRL through the clawock pipeline, Eastmoney for HK) as verification, and third-party summaries allowed only to fill a gap, at the cost of a lower source grade. The output is a structured artifact, not a narrative: the code computes the source grade (A, B or C), cash conversion, free cash flow, working-capital gaps, dilution, share-based compensation share, margins, and whether guidance beat, matched or missed, while you read the filing and choose which segments and footnotes matter. A promise ledger rolls forward from period to period and promises are never dropped: each lands as met, partial, missed, not due or unverifiable on evidence you locate. Every published number needs two independent sources in the provenance manifest, and the release gate refuses the artifact when a number is single-sourced or the two sources disagree beyond tolerance. The comparable...

- Listing: https://theskillharbor.com/products/earnings-review
- Fiche en français: https://theskillharbor.com/fr/products/earnings-review
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/KCNyu/clawock/blob/master/skills/earnings-review/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
