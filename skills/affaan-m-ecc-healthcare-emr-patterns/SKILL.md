<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-healthcare-emr-patterns
description: "Build EMR/EHR with Muse the safe way: patient-safety-first encounter flows, medication safety with..."
---

# Healthcare EMR Patterns

Curated by Skill Harbor: development patterns for electronic medical records that put patient safety ahead of everything, contributed by Dr. Keyur Patel (Health1 Super Speciality Hospitals). Every design decision is evaluated against one question: could this harm a patient. The encounter flow runs vertically on a single page with a sticky patient header showing allergies and active medications, from chief complaint through history, examination, vitals with auto-calculated clinical scores, diagnosis with ICD-10 and SNOMED search, medications with drug interaction checking, investigations, and plan to sign and lock. The medication safety pattern blocks prescribing on critical interactions by default, requiring a documented override reason stored in the audit trail, while major interactions need active acknowledgment. Red flags trigger non-dismissable alerts, never toasts. Once signed, an encounter locks completely and only an addendum, a separate linked record, can add information. Clinical UI patterns cover vitals display with range highlighting and trend arrows, lab results with critical value alerts, one-click prescription PDFs, and stricter accessibility than typical web apps: 4.5:1 contrast, large touch targets for gloved hands, no color-only indicators, no auto-dismissing toasts for clinical alerts. By @affaan-m, listed here with credit to its creator and contributor. From the affaan-m/ECC repository (MIT). Honest caveats: patterns do not make an app compliant or...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-healthcare-emr-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-healthcare-emr-patterns
- Category: Healthcare
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/healthcare-emr-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
