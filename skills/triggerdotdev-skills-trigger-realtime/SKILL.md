<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: triggerdotdev-skills-trigger-realtime
description: "The consumer side of Trigger.dev runs — subscribe to live run state, render AI/text streams..."
---

# Trigger.dev realtime: live run updates and streams in your frontend

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @triggerdotdev's trigger-realtime skill — the consumer side of Trigger.dev's run state and streams (not the backend task authoring; that's trigger-tasks territory). It covers the frontend stack: subscribe to runs in realtime (runs.subscribeToRun and the useRealtimeRun hook), consume metadata and AI/text streams in React (useRealtimeStream), trigger tasks from the browser (useTaskTrigger, useRealtimeTaskTrigger), mint scoped frontend credentials in the backend (auth.createPublicToken for read/subscribe, auth.createTriggerPublicToken for single-use browser triggering — both defaulting to 15-minute expiry), send input back into a running task (useInputStreamSend), complete wait tokens from React (useWaitToken), and subscribe from the backend via async iterators. The flow is always the same: mint a scoped token in the backend, pass it to the frontend, subscribe with a hook. It also carries a common-mistakes list (never trigger from the browser with a read-only Public Access Token, never mint a scopeless token, never poll with useRun, always "use client", always skipColumns payload/output for status badges, guard subscribes on the handle). Honest caveats: the skill is bundled inside @trigger.dev/sdk and read from node_modules, so it matches your installed SDK version; you need a Trigger.dev project with a backend task to consume — frontend-only reading of the skill teaches nothing...

- Listing: https://theskillharbor.com/products/triggerdotdev-skills-trigger-realtime
- Fiche en français: https://theskillharbor.com/fr/products/triggerdotdev-skills-trigger-realtime
- Category: Backend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/triggerdotdev/skills/blob/main/trigger-realtime/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
