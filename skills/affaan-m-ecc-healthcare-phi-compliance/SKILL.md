<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-healthcare-phi-compliance
description: "Protect patient data with Muse: PHI classification, row-level security, tamper-proof audit trails..."
---

# Healthcare PHI Compliance Patterns

Curated by Skill Harbor: compliance patterns for protecting patient and clinician data in healthcare applications, contributed by Dr. Keyur Patel (Health1 Super Speciality Hospitals). Protection works on three layers: classification (what is sensitive), access control (who can see it), and audit (who did see it). PHI is defined as any data that can identify a patient and relates to their health, from names and national IDs to diagnoses, medications and claim details. Access control uses row-level security with facility-scoped policies and insert-only, tamper-proof audit logs. Schema tagging marks PHI and PII columns at the database level. The most practical part is the catalog of common leak vectors: patient data in error messages thrown to the client, full patient objects in console output, identifying data in URL parameters, PHI in browser localStorage, service_role keys in client-side code, and full patient records in logs and error tracking. Each comes with the safe alternative, like opaque UUIDs instead of medical record numbers and generic errors with server-side logging. A deployment checklist closes the skill: no PHI in errors, logs, URLs or browser storage, RLS enabled on all PHI tables, audit trails on, cross-facility isolation verified. By @affaan-m, listed here with credit to its creator and contributor. From the affaan-m/ECC repository (MIT). Honest caveats: patterns do not make an app HIPAA or GDPR compliant by themselves, a real compliance review is required...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-healthcare-phi-compliance
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-healthcare-phi-compliance
- Category: Healthcare
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/healthcare-phi-compliance/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
