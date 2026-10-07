<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-platform-policy-rule-generate
description: "Author PolicyRuleDefinition and PolicyRuleDefinitionSet metadata for Salesforce Data Cloud..."
---

# Data Cloud policy rule authoring

Honest caveats: gated on the `EnforceOMatic` and `PolicyRuleMDAPI` org permissions, min API v64.0 (66.0 for `PolicyJsonExpression` conditions); some shapes are not authorable via MDAPI at all (identified-guest record access, `SCALAR`/`PLURAL_ATTRIBUTE` paths need a runtime RuleProvider); the agent's user-facing text must never name internal engines or implementation internals (the skill's output-hygiene rules). Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-platform-policy-rule-generate
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-platform-policy-rule-generate
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/skills/platform-policy-rule-generate/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
