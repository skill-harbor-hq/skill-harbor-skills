<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-esign-field-placement
description: "Deterministic e-signature field placement via browser automation: numeric coordinates, fixed..."
---

# E-Signature Field Placement

Curated by Skill Harbor: a deterministic method for placing signature, date and text fields in a web e-signature composer through a browser automation session, written as a workflow contract rather than an executable controller. Uses numeric Location panel coordinates instead of drag for repeatable positions, a fixed signature page layout (your block first: By, Name, Title, Email, Date, then the counterparty block), correct per-recipient ownership, and a hard gate before anything is sent or signed, with save-as-draft as the default. Preconditions: the browser session is already signed in by a human and the automation never enters credentials or one-time codes (a login redirect prints LOGGED OUT and exits non-zero); every sensitive read and mutation is validated against a trusted configuration of exact HTTPS origins and document identity, with no substring or domain-suffix matching. Includes document geometry calibration, screenshot capture and a draft envelope for operator review before send. From the affaan-m/ECC repository (MIT). Honest caveats: pairs with the master-agreement-generator skill for generated agreements; placement reliability depends on the composer's DOM stability. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-esign-field-placement
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-esign-field-placement
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/esign-field-placement/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
