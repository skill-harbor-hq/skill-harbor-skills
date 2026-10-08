<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-healthcare-eval-harness
description: "Patient-safety deployment gates for healthcare apps with Muse: CDSS accuracy, PHI exposure, and..."
---

# Healthcare Eval Harness

Curated by Skill Harbor: an automated patient-safety verification system that makes Muse gate healthcare application deployments on five test categories. The first three are CRITICAL gates requiring a 100% pass rate, where a single failure blocks deployment: CDSS accuracy (drug interaction pairs in both directions, dose validation rules, clinical scoring against published specs, no false negatives, no silent failures), PHI exposure (leaks in API error responses, console output, URL parameters, browser storage, cross-facility isolation, unauthenticated access), and data integrity (locked encounters, audit trail entries, cascade delete protection, concurrent edits, no orphaned records). The remaining two are HIGH gates at 95%+: clinical workflow (encounter lifecycle, medication sets, prescription PDFs, red flag alerts) and integration compliance (HL7 v2.x parsing, FHIR validation, lab result mapping). The skill ships copy-ready CI pipelines that run critical gates with bail-on-first-failure semantics, anti-patterns to avoid (never mock the CDSS engine in integration tests, never lower critical thresholds below 100%), and an eval report template with a SAFE TO DEPLOY verdict. Contributed by Dr. Keyur Patel (Health1 Super Speciality Hospitals). By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: examples use Jest, adapt commands to your framework; gates test what you wrote tests for, they do not replace clinical review or...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-healthcare-eval-harness
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-healthcare-eval-harness
- Category: Healthcare
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/healthcare-eval-harness/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
