<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-scientific-db-uspto-database
description: "Official USPTO patent and trademark records: PatentSearch, TSDR, assignments, and reproducible IP..."
---

# USPTO Database

Curated by Skill Harbor: a data-gathering workflow for official United States patent and trademark records from USPTO systems. It prefers official surfaces first (Open Data Portal, Patent File Wrapper, PatentSearch API, TSDR Data API, assignment search, PTAB data) and treats secondary indexes like Google Patents or Lens.org as convenience only, cross-checking the official record whenever the answer matters. Includes a PatentSearch JSON query workflow with a Python request skeleton (explicit filters, deterministic sort and pagination), a TSDR workflow for trademark status, documents, and owner history (normalize serial numbers, respect the lower rate limits on document downloads), file-wrapper and prosecution-history lookup, an assignment workflow (conveyance text, execution vs. recordation dates, distinguishing assignment records from legal ownership conclusions), and a reproducible research log table separating official facts from inferred analysis. Ends with a review checklist: official source first, endpoints verified before running code, keys kept out of files and logs, rate limits respected, legal conclusions escalated. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: requires USPTO/PatentsView API keys for the API flows (see the prerequisites in the install prompt); data gathering only, it gives no legal advice and flags ownership conclusions for attorney review. Skill Harbor never reviews the code, review it...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-scientific-db-uspto-database
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-scientific-db-uspto-database
- Category: Research
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/scientific-db-uspto-database/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
