<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: modbender-familysearch
description: "Explore your family history: live FamilySearch API or offline GEDCOM parsing."
---

# FamilySearch Genealogy Skill for Muse

Search, explore, and analyze family history in two modes. Live API mode queries FamilySearch directly — person search by name/dates/places, ascending pedigrees up to 8 generations (Ahnentafel numbering), descendants, parents, spouses, children, and historical records — through bundled Python scripts with caching and an OAuth flow that stores tokens in the OS keychain (never passwords). Offline mode parses exported `.ged` files from FamilySearch, Ancestry, or MyHeritage — fuzzy name search, full profiles, pedigree charts, narrative biographies, timelines, tree statistics, and common-ancestor search for files up to ~100K individuals. Beyond retrieval it supports narrative genealogy: connecting facts to stories, flagging research opportunities like missing records or conflicting dates. Discovered via skills.sh. Honest note: the live mode needs a free FamilySearch account plus a developer app key and an OAuth dance — not instant; the offline mode only needs a GEDCOM export. The repo is a skill library, so install both scripts alongside the SKILL.md. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/modbender-familysearch
- Fiche en français: https://theskillharbor.com/fr/products/modbender-familysearch
- Category: Family
- Price: Free
- Verification: unverified
- Source repo: https://github.com/modbender/skill-library-mcp/blob/HEAD/data/familysearch/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
