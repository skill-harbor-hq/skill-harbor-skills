<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-cli-gws-modelarmor-sanitize-response
description: "Run model output through a Model Armor template with the gws CLI for outbound safety checks"
---

# Sanitize an LLM response through Google Model Armor

💳 **Paid API required** — this skill drives Google Cloud's Model Armor through the gws CLI; Model Armor screening is billed per request, with no usable free tier stated. Curated by Skill Harbor — @googleworkspace's outbound-safety wrapper: sanitize a model response through a Model Armor template with `gws modelarmor +sanitize-response --template projects/PROJECT/locations/LOCATION/templates/TEMPLATE --text 'model output'` (or pipe model output into it, or pass a full JSON body), with companion coverage for inbound safety via `+sanitize-prompt`. By @googleworkspace, listed here with credit to its creator. Honest caveats: requires the gws CLI, a Google Cloud project with Model Armor enabled and an existing template; read the sibling gws-shared skill for auth and security rules before use; Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/googleworkspace-cli-gws-modelarmor-sanitize-response
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-cli-gws-modelarmor-sanitize-response
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/gws-modelarmor-sanitize-response/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
