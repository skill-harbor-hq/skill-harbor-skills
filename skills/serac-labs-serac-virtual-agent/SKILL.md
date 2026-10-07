<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: serac-labs-serac-virtual-agent
description: "Build ServiceNow Virtual Agent topics from the agent — sys_cs_topic conversations, topic blocks..."
---

# Virtual Agent for ServiceNow — conversational self-service topics and NLU

Curated by Skill Harbor — @serac-labs's virtual-agent skill, listed here with credit to its creator: a builder playbook for ServiceNow Virtual Agent — creating topics on `sys_cs_topic` (worked password-reset example: NLU model, utterances like "reset my password", custom entities like application_name, variables, category), assembling topic flows from block types (text, prompt, script, decision, link, handoff to a live agent), defining NLU intents and training phrases, adding quick replies and suggestion chips, typing indicators, and KB/incident integration scripts that look up users and create tickets. It documents the key tables (`sys_cs_topic`, `sys_cs_topic_block`, `sys_cs_intent`, `sys_cs_utterance`, `sys_cs_entity`) and the available agent tools (snow_create_va_topic, snow_train_va_nlu, snow_query_table, snow_artifact_manage). Honest caveats: everything here runs inside a ServiceNow instance — you need one to use it (ServiceNow offers a free Personal Developer Instance for dev work; production requires a licensed instance) — and the agent tools it references assume the Serac skill/tooling environment is configured; topic scripts execute server-side GlideRecord code, so review generated scripts before publishing to a live VA — a bad script can write to production tables. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/serac-labs-serac-virtual-agent
- Fiche en français: https://theskillharbor.com/fr/products/serac-labs-serac-virtual-agent
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/serac-labs/serac/blob/main/packages/skills/virtual-agent/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
