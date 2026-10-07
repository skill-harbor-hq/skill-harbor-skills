<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: idanbeck-claude-skills-gmail-skill
description: "Multi-account Gmail access for agents via a Python CLI: search, read, send, draft, labels, stars..."
---

# Gmail skill: read, search, send and draft Gmail emails and contacts

Curated by Skill Harbor — @idanbeck's Gmail skill: multi-account Gmail and Google contacts access for agents through a Python CLI (`gmail_skill.py`), with a mandatory user-confirmation rule before any email is sent (the agent must show full email details and get explicit approval first — no exceptions). Covers search (Gmail query syntax), read, list, send, mark read/unread, archive/unarchive, star/unstar, drafts with reply threading (`--reply-to-id` for proper In-Reply-To/References headers), labels, contact search, and account management; tokens stored locally per account. One-time setup (~2 min): create a Google Cloud OAuth desktop-app client, enable Gmail API and People API, grant scopes, download the JSON credentials. Honest caveats: the agent can send real emails from your accounts — the confirmation rule is the only safety net, keep it; apps in OAuth "testing" mode may need re-auth every 7 days unless published. Short listing: license could not be verified from the source metadata, so this fiche links only to the original repo — read it there. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/idanbeck-claude-skills-gmail-skill
- Fiche en français: https://theskillharbor.com/fr/products/idanbeck-claude-skills-gmail-skill
- Category: Productivity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/idanbeck/claude-skills/blob/main/gmail-skill/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
