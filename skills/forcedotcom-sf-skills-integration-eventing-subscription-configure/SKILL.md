<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: forcedotcom-sf-skills-integration-eventing-subscription
description: "Create, read, update or delete ManagedEventSubscription metadata for Salesforce platform event..."
---

# Managed event subscriptions configurator

Honest caveats: requires the sf CLI and an org on API v60.0+; it does NOT create the event channel itself (that's a separate skill); `EARLIEST` replay on a high-volume channel can replay up to 72 hours of backlog on activation — always confirm with the user; deleting a subscription permanently discards its replay state. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/forcedotcom-sf-skills-integration-eventing-subscription-configure
- Fiche en français: https://theskillharbor.com/fr/products/forcedotcom-sf-skills-integration-eventing-subscription-configure
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/forcedotcom/sf-skills/blob/main/plugins/builder/integration/skills/integration-eventing-subscription-configure/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
