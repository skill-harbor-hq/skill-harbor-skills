<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-hipaa-compliance
description: "HIPAA entrypoint for Muse on US healthcare work: PHI decision gates, minimum necessary access, BAA..."
---

# HIPAA Compliance

Curated by Skill Harbor: the HIPAA-specific entrypoint for Muse when a task is explicitly about US healthcare compliance. It stays intentionally thin and canonical, routing the concrete implementation work to companion skills (PHI handling rules, healthcare code review, general security review) while applying HIPAA-specific decision gates: is this data PHI, is this actor a covered entity or business associate, does the vendor need a BAA before touching the data, is access limited to the minimum necessary, and are read/write/export events auditable. The guardrails are blunt: never place PHI in logs, analytics events, crash reports, prompts, or client-visible error strings; never expose PHI in URLs, browser storage, screenshots, or example payloads; treat third-party SaaS, observability, support tooling and LLM providers as blocked-by-default until BAA status is clear; prefer opaque internal IDs over names, phone numbers or addresses. Includes worked examples (AI visit summaries for a clinician dashboard, support transcripts into analytics) showing how the gates apply in practice. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is guidance, not legal advice; following a checklist does not make you HIPAA compliant, a real compliance review still belongs to your compliance officer and counsel. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-hipaa-compliance
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-hipaa-compliance
- Category: Healthcare
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/hipaa-compliance/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
