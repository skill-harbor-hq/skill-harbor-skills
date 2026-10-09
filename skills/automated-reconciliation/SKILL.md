<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: automated-reconciliation
description: "Match bank statements to the general ledger at scale: deterministic matching first, fuzzy matching..."
---

# Automated Reconciliation

⚠️ **Finance warning / Avertissement finance** : informational only, not investment advice. A reconciliation that forces matches hides real errors and real fraud: a wrong match rate taken at face value can conceal missing cash, there is a real risk of loss in any close decision taken from an unreconciled balance, and no output here is a promise of return. Curated by Skill Harbor: the automated reconciliation skill of GAJETOso/financeskills. Use it to match disparate financial data sources at scale, bank statements against the general ledger or an ERP export, invoices against payments, without weeks of manual ticking. The skill is honest about its own technical limit up front: language models are not good at matching 50,000 rows, so large datasets run through Python libraries such as pandas and RecordLinkage, and the model is used where it is actually strong, resolving the ambiguous matches, roughly the 5 percent the code cannot settle. The framework runs in priority order: data cleaning first (standardizing vendor names, so AWS and Amazon Web Svcs become one counterparty), deterministic matching on exact identifiers, amounts and dates, probabilistic fuzzy matching on similar names with the same amount inside a two day window using Jaro-Winkler or Levenshtein distance, and exception handling that flags what could not be matched instead of forcing it. The technical steps add a tolerance window on amounts (within five cents for rounding), many-to-one resolution (one bank...

- Listing: https://theskillharbor.com/products/automated-reconciliation
- Fiche en français: https://theskillharbor.com/fr/products/automated-reconciliation
- Category: Finance
- Price: Free
- Verification: unverified
- Source repo: https://github.com/GAJETOso/financeskills/blob/main/skills/automated-reconciliation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
