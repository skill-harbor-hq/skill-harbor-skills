<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pont-muse-hermes
description: "Cloud brain plans, local hands act, approvals stay local."
---

# Hermes Bridge

Connect a cloud Muse to a Hermes agent already running on your Windows PC, without opening an inbound port on that PC and without recreating your sessions somewhere else. The cloud assistant keeps planning and checking. The local agent does the work on your real PC, already logged in, with your files and applications already open.

The link is a token mailbox. The brain deposits a task, the PC comes out to fetch it, the local agent executes it and posts the result back, and the brain reads that result. Two separate tokens keep the roles apart: the brain token can deposit and read, but cannot fetch or answer, and the Hermes token can fetch and answer, but cannot create or list tasks. A compromised or injected local agent therefore cannot give itself orders.

Safety comes before speed. The first run is read-only only: list names, report, write nothing. Anything else, writing, modifying, deleting, installing, sending or paying, is refused by default and posted back as APPROVAL NEEDED. A writing mandate must come from you in person, in your chat with the local agent, and be written into the polling job's own orders, not just said in a chat and not just written in a task. The brain never approves a run remotely through an API. Approvals stay with you, locally. A run waiting for approval expires or fails, that is the rule.

Autonomous rounds are optional and need their own go. Once set up, the local agent polls the mailbox on a schedule, at most one task per round, silently when...

- Listing: https://theskillharbor.com/products/pont-muse-hermes
- Fiche en français: https://theskillharbor.com/fr/products/pont-muse-hermes
- Category: Developer tools
- Price: Free
- Verification: verified
- Source repo: n/a

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
