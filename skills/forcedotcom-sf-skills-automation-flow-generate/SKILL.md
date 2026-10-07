<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-automation-flow-generate
description: "Generate Salesforce Flow metadata (Screen, Autolaunched, Record-Triggered, Scheduled) with the..."
---

# Generate Salesforce Flows via a strict 3-step MCP pipeline

Curated by Skill Harbor — @forcedotcom's skill for generating Salesforce Flow metadata through one mandatory 3-step MCP pipeline (`execute_metadata_action`), for Screen, Autolaunched, Record-Triggered (before/after-save) and Scheduled flows. Step 1, `fetchGroundedObjectMetadata`: pass the user's natural-language prompt plus `inflightMetadata` — an ARRAY of custom objects/fields scanned from the local sfdx project (exact naming conventions: `apiName`, `type`, `referenceTo`; `[]` when none). Step 2, `flowElementSelection`: same userPrompt, the groundingMetadata string passed verbatim, and an operationId. Step 3, `flowElementGeneration`: loop with the same operationId and `requestSource: "A4V"` until `isComplete` is true — never pause, never ask to continue, no matter how many iterations. Strict constraints: never create or modify flow XML outside the pipeline, never add/remove nodes from what the pipeline returned. Multi-flow requests must be split into N separate, sequential single-flow pipelines. Includes pattern guidance (scheduled-flow cadence lives on the start element's `<schedule>` block; counts via a single `AssignCount` assignment; never invent actions the prompt didn't request) and a canvas-mode check. Honest caveats: requires Salesforce org access (a free Developer Edition org works) plus the Salesforce CLI and an MCP server exposing `execute_metadata_action` (metadata-experts >= 1.0.0) — generation only, you still deploy and test yourself; test generated flows in a...

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-automation-flow-generate
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-automation-flow-generate
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/plugins/builder/salesforce-development/skills/automation-flow-generate/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
