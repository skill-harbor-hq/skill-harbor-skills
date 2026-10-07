<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: medusajs-medusa-agent-skills-building-storefronts
description: "Frontend integration skill for Medusa storefronts — always use the JS SDK (never plain fetch), use..."
---

# Build Medusa storefronts: JS SDK patterns, React Query, price rules

Selected by Skill Harbor — short listing (the repo's license is unknown, so no content is reproduced): @medusajs's official storefront development skill — the frontend integration playbook for building storefronts on Medusa. Core rules, ranked by priority: SDK usage is CRITICAL — ALWAYS use the Medusa JS SDK for every API request and never plain fetch() (missing publishable-api-key/auth headers cause silent failures); for built-in endpoints use existing SDK methods, for custom routes use sdk.client.fetch(); React Query patterns are HIGH priority — useQuery for GETs, useMutation for mutations, invalidate on success, hierarchical query keys, always handle loading and error states; data display has one critical rule — prices are stored as-is ($49.99 = 49.99), NEVER divide by 100 when displaying; plus a common-mistakes checklist (no JSON.stringify on bodies — the SDK serializes, no manual Content-Type headers, don't hardcode SDK import paths). Companion to the building-with-medusa backend skill (Module → Workflow → API Route); the MedusaDocs MCP server is explicitly secondary — skills come first. Honest caveats: the quick reference is NOT sufficient for implementation — the skill demands loading references/frontend-integration.md before writing code; the repo's license is unknown — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/medusajs-medusa-agent-skills-building-storefronts
- Fiche en français: https://theskillharbor.com/fr/products/medusajs-medusa-agent-skills-building-storefronts
- Category: E-commerce
- Price: Free
- Verification: unverified
- Source repo: https://github.com/medusajs/medusa-agent-skills/blob/main/plugins/medusa-dev/skills/building-storefronts/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
