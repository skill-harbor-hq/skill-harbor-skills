<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-i18n-sync
description: "Keep app translations in sync: translate and review JSON locale files using source-key usage and..."
---

# i18n Sync

Curated by Skill Harbor: a workflow skill for translating and synchronizing application JSON locale files without wrecking the ones you already have. Instead of translating strings in a vacuum, it reads where each key is actually used in the product, preserves the project's JSON structure, interpolation syntax, and unrelated translations, and applies your project's terminology and glossary. Typical jobs: new source keys needing target-language translations, a brand-new target language, source copy that changed and needs existing translations re-reviewed, or a full pass for missing and stale keys. It produces a reviewable patch and applies it through your project's existing serializer or precise file edits, never by bolting on a second localization engine. Scope discipline is built in: it identifies the authorized project, source locale, target locales, and exact files first, and stops at a proposal if ownership or write scope is unclear. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: built for JSON locale files, other formats need adaptation; translation quality depends on the provider your agent uses, it does not promise local-only translation; confirm the file list before letting it edit. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-i18n-sync
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-i18n-sync
- Category: Localization
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/i18n-sync/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
