<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: apify-agent-skills-apify-generate-output-schema
description: "Analyze an Actor's source to produce dataset_schema.json, output_schema.json and..."
---

# Generate Apify Actor output schemas from source code

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @apify's skill for generating Actor output schemas — the files that tell Apify Console how to display run results. A 7-phase workflow: Phase 1 discovers the Actor structure (locate the `.actor/` directory, read `actor.json`, find every `pushData`/`setValue` call, reuse existing TypeScript interfaces or Python TypedDicts rather than re-analyzing, and match conventions of existing schemas in the repo); Phase 2 generates `dataset_schema.json` (all output fields in `properties`, every field `nullable: true`, `additionalProperties: true` and `required: []` at both top level and nested objects, anonymized examples); Phase 3 generates `key_value_store_schema.json` with collections grouped by fixed keys or key prefixes; Phase 4 generates the minimal `output_schema.json` (linking to dataset/KV store via template variables); Phase 5 wires everything into `actor.json`; Phase 6 reviews against a checklist; Phase 7 summarizes. Honest caveats: works on an Actor codebase the agent can read — not standalone; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/apify-agent-skills-apify-generate-output-schema
- Fiche en français: https://theskillharbor.com/fr/products/apify-agent-skills-apify-generate-output-schema
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/apify/agent-skills/blob/main/skills/apify-generate-output-schema/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
