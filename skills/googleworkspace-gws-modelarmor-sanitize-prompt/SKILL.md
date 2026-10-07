<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: googleworkspace-gws-modelarmor-sanitize-prompt
description: "Screen user prompts through a Google Model Armor template before they reach your model"
---

# 💳 Model Armor Sanitize Prompt (gws CLI)

💳 Requires a paid Google Workspace account for the gws CLI — no free tier. Curated by Skill Harbor — a real safety utility, not a gadget: it runs a user prompt through a Google Model Armor template (`gws modelarmor +sanitize-prompt --template projects/PROJECT/locations/LOCATION/templates/TEMPLATE`) with `--text`, `--json` or stdin input, and points at `+sanitize-response` for the outbound direction. No other fiche in the catalog covers Model Armor. By @googleworkspace, listed here with credit to its creator. Honest caveats: you need a provisioned Model Armor template in a Google Cloud project (the template resource name is required), the gws binary installed and authenticated, and the gws-shared skill read first for auth and security rules; sanitization is a screening layer, not a guarantee — it reduces risk, it doesn't eliminate it. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/googleworkspace-gws-modelarmor-sanitize-prompt
- Fiche en français: https://theskillharbor.com/fr/products/googleworkspace-gws-modelarmor-sanitize-prompt
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/googleworkspace/cli/blob/main/skills/gws-modelarmor-sanitize-prompt/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
