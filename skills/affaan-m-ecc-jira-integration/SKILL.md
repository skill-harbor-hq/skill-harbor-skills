<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-jira-integration
description: "Work Jira tickets from inside your Muse session: fetch requirements, extract acceptance criteria..."
---

# Jira Integration

Curated by Skill Harbor: a Jira bridge for the AI coding workflow, with two paths. Option A, recommended: the mcp-atlassian MCP server wired into the MCP config with JIRA_URL, JIRA_EMAIL, and JIRA_API_TOKEN in the environment, exposing search, create, update, comment, and transition tools directly to the agent. Option B: direct Jira REST API v3 calls via curl or helper scripts, with the same environment variables and credentials kept out of command lines and source. The skill covers fetching a ticket to understand requirements, extracting testable acceptance criteria, adding progress comments, transitioning status from To Do to In Progress to Done, linking merge requests and branches to issues, and searching by JQL. Security guidance is explicit: never hardcode secrets, prefer environment or a secrets manager, keep tokens out of committed files. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: you need a real Jira instance and an API token from id.atlassian.com; the skill assumes you already have Jira access, it does not create it. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-jira-integration
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-jira-integration
- Category: Project Management
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/jira-integration/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
