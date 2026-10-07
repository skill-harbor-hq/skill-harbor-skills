<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: google-labs-code-stitch-skills-stitch-design
description: "Turn existing frontend code into a Stitch design — HTML extraction, design-system extraction, upload"
---

# Stitch Code to Design

💳 Curated by Skill Harbor — an orchestrator skill (its real name is `stitch::code-to-design`) that moves existing frontend code — React, Vite, Next.js, Angular, Vue — into a Google Stitch design for further iteration. It chains three sibling skills in sequence: extract a single self-contained HTML file from the build output or dev server, extract a design system (`DESIGN.md`) from the source code including Angular configs and theme files, then upload both to a Stitch project with a Stitch API key. Requires the sibling skills in the same repo (extract-static-html, extract-design-md, upload-to-stitch / manage-design-system), a target Stitch `projectId`, and a Stitch API key — a paid service. Honest notes: this listing covers only the orchestrator file; the siblings are separate skills not included here, and the skill never verifies extraction output automatically (browser spot-check is user-driven). By @google-labs-code, listed here with credit to its creator. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/google-labs-code-stitch-skills-stitch-design
- Fiche en français: https://theskillharbor.com/fr/products/google-labs-code-stitch-skills-stitch-design
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/google-labs-code/stitch-skills/blob/main/plugins/stitch-design/skills/code-to-design/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
