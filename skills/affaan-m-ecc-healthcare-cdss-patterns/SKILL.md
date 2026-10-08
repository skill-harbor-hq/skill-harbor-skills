<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-healthcare-cdss-patterns
description: "Clinical Decision Support patterns: drug interaction checking, dose validation, NEWS2/qSOFA..."
---

# Healthcare CDSS Patterns

Curated by Skill Harbor: patterns for building Clinical Decision Support Systems that integrate into EMR workflows, contributed by Dr. Keyur Patel (Health1 Super Speciality Hospitals), listed here with credit. CDSS modules are patient-safety critical with zero tolerance for false negatives, so the engine is designed as a pure function library with zero side effects: clinical data in, alerts out, fully testable. Three primary modules: checkInteractions, which checks a new drug against current medications and known allergies and returns severity-sorted InteractionAlert values using a DrugInteractionPair model (severity critical, major or minor, with mechanism, clinical effect and recommendation); validateDose, which validates a prescribed dose against weight-based, age-adjusted and renal-adjusted rules; and calculateNEWS2, which computes the National Early Warning Score 2 from vitals with total score, risk level and escalation guidance. Covers clinical scoring systems (NEWS2, qSOFA, APACHE, GCS), alert severity classification, medication order entry with safety checks, and lab result interpretation in clinical context. From the affaan-m/ECC repository (MIT). Honest caveats: design patterns only, they do not replace clinical review or regulatory compliance; never paste real patient data (PHI) into a chat. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-healthcare-cdss-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-healthcare-cdss-patterns
- Category: Healthcare
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/healthcare-cdss-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
