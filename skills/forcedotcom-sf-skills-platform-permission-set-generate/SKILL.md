<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-platform-permission-set-generate
description: "Generate deployable Salesforce permission set metadata — CRUD object permissions, field-level..."
---

# Generate Salesforce PermissionSet XML: object, field, user and app permissions

Curated by Skill Harbor — @forcedotcom's skill for generating correct, deployable Salesforce PermissionSet XML: an 8-step workflow — core properties (descriptive API names like `Sales_Manager_Access`, fullName/label/description); CRUD object permissions (`allowCreate/Read/Edit/Delete`, `modifyAllRecords`, `viewAllRecords`, `viewAllFields`); field-level security with the hard rule that required fields must NEVER appear in `<fieldPermissions>` (deployment fails — confirm from object metadata first; formula fields can't be editable); user permissions (`ApiEnabled`, `ViewSetup`, `ManageUsers`, `RunReports`) with a security-review flag on `ViewAllData`, `ModifyAllData` and `ManageUsers`; app and tab visibility (tab naming: `__c` for custom tabs, `standard-` prefix for standard tabs); optional Apex class and Visualforce page access; license and record-type settings; Agentforce employee-agent access. Honest caveats: permission sets GRANT ACCESS — follow least privilege, never deploy an unreviewed permission set to production, and test in a sandbox first; you deploy with the Salesforce CLI against your own org. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-platform-permission-set-generate
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-platform-permission-set-generate
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/plugins/builder/salesforce-development/skills/platform-permission-set-generate/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
