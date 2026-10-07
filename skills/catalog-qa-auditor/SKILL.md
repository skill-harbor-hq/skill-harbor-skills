<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: catalog-qa-auditor
description: "Audit a product catalog for silent data corruption: empty prompts, duplicates, template residue..."
---

# Catalog QA Auditor

The Catalog QA Auditor catches the errors nobody finds by opening listings one by one. It runs automated read-only scans over a product database, surfaces only the anomalies, and fixes them with a re-read after every write. It was built for a 1,900-listing directory where a full audit costs a few thousand tokens instead of a full catalog read, and it has caught real incidents: installation prompts containing literally nothing but a code fence, the same prompt pasted onto the wrong listing, and prices contradicting their own labels.

The check list covers installation prompts (empty, corrupted, or duplicated across listings), template residue ({{ }}, TODO, lorem, [insert markers in user-facing text), missing translations (EN present but FR empty), invalid or empty creation dates (which break "New" sections and date sorting), duplicate repo URLs (normalized before comparison, so /blob/... suffixes and root URLs are both caught), price inconsistencies (paid flag vs price vs label), secrets and PII swept from texts (API keys and emails pasted by accident are invisible to the naked eye), orphaned sellers and suspicious slugs, and sitemap vs database counts (a gap means an incomplete build). Link health runs quarterly in the background because thousands of HTTP requests are slow.

The workflow is monthly, plus after any data incident, with a dated corrections log for every run. The operating rules are strict: scans are SELECT-only, dedupe happens on slugs and ids never on display...

- Listing: https://theskillharbor.com/products/catalog-qa-auditor
- Fiche en français: https://theskillharbor.com/fr/products/catalog-qa-auditor
- Category: Developer Tools
- Price: Free
- Verification: verified
- Source repo: n/a

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
