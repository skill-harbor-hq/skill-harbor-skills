<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-scientific-db-pubmed-database
description: "Direct PubMed and NCBI E-utilities workflows: MeSH queries, PMID lookup, citation retrieval, and..."
---

# PubMed Database

Curated by Skill Harbor: a research skill for biomedical literature that goes straight to PubMed instead of general web search. It teaches query construction with Boolean operators and PubMed field tags (title, abstract, author, journal, MeSH, publication type, date, language), MeSH term and subheading syntax, and publication-type plus date filters for systematic-review style passes. The NCBI E-utilities workflow (esearch, esummary, efetch, elink) comes with a Python example for repeatable, API-backed literature monitoring, plus output discipline: record the exact search string, database, date searched, filters, and result count so any pass is reproducible. A review checklist covers valid field tags, MeSH plus free-text pairing for newer topics, explicit date ranges, API keys loaded from the environment, and rate-limit respect. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; an NCBI API key and email are recommended for production scripts (keep keys in environment variables, never in committed files), and this is a literature-search tool, not medical advice. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-scientific-db-pubmed-database
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-scientific-db-pubmed-database
- Category: Research
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/scientific-db-pubmed-database/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
