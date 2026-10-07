<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-platform-list-view-generate
description: "Generate Salesforce List View metadata — label/fullName rules, filterScope, filter/operation/value..."
---

# Author deployable Salesforce List View metadata XML

Curated by Skill Harbor — @forcedotcom's skill for generating deployable Salesforce List View metadata: the critical rules (custom fields use exact API names like `Status__c`, never labels; standard fields on custom objects use the defined names — NAME, OWNER.ALIAS, CREATED_DATE, LAST_UPDATE; operations must match field types — equals/notEqual for picklists, 0/1 for booleans, no text-only operators on non-text fields; file name, fullName and uniqueness must align; files go under `objects/<Object>/listViews/`); a 6-step workflow (gather the target object and requirements → examine existing examples in the repo/org → write a spec: fullName, label under 40 chars, filterScope, filters, booleanFilterLogic, ordered columns → author the XML → validate locally → deploy and verify in the UI); the visibility strategy decision (all users vs owner-only/restricted, defaulting to all users); column-density guidance; and a common deployment errors table with fixes. Honest caveats: methodology plus XML authoring — you still deploy with the Salesforce CLI against your own org; every field name and picklist value must exist in the target org's schema or deployment fails. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-platform-list-view-generate
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-platform-list-view-generate
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/plugins/builder/salesforce-development/skills/platform-list-view-generate/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
