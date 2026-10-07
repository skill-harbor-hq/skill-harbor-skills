<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: adobe-skills-reskin
description: "Rebuild an existing site's pages with byte-faithful content (text, ordered images, SEO metadata) on..."
---

# Reskin — rebuild a site's pages with byte-faithful content on a donor design system

Curated by Skill Harbor — @adobe's reskin skill (part of the Stardust chain): rebuild an existing site's pages so every visible byte of content survives — whitespace-normalized visible text, the ordered visible-image set, full SEO metadata carry-over — while the surface comes entirely from a donor's tokens and module vocabulary (another live site, or local static HTML prototypes; Figma donors are contract-defined but not yet implemented). The decisive rule: the page is generated programmatically from the captured content model — content strings are never retyped; byte fidelity then holds by construction and the gate becomes a regression check. Six phases: ingest the donor (curated probe-able token sheet + enumerated module vocabulary, pinning one reference page per module family), byte-oriented content-model capture (mandatory scope declaration, executable normalization ledger), a mapping brief (≥80% of content slots mapped onto named donor modules), programmatic render from the model's ordered stream, three gate families (content byte-equality, design-adoption probe, sanity), then handoff to the existing migrate/deploy skills. Honest caveats: heavy setup — requires Node 22+, Playwright with Chromium, playwright-cli on PATH, and the impeccable skill installed alongside; not for redesigning from intent or for migrating while keeping the current design (those are the sibling extract/replica flows). Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself...

- Listing: https://theskillharbor.com/products/adobe-skills-reskin
- Fiche en français: https://theskillharbor.com/fr/products/adobe-skills-reskin
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/adobe/skills/blob/main/plugins/stardust/skills/reskin/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
