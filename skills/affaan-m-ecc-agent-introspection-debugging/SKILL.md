<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-agent-introspection-debugging
description: "A structured capture, diagnose, recover loop for failing agent runs instead of blind retries."
---

# Agent Introspection Debugging

Curated by Skill Harbor: a structured self-debugging workflow for AI agent failures, built for the moment an agent run fails repeatedly, burns tokens without progress, loops on the same tools, or drifts away from its task. Instead of retrying blindly, the skill teaches a four-phase loop: capture the failure precisely (error, last meaningful tool sequence, what the agent was trying to do, context pressure, environment assumptions) with a minimum capture template, diagnose the common agent-specific failure patterns, apply contained recovery actions, and produce a structured human-readable introspection report. It sets scope boundaries too: use it for failure capture and diagnosis, not as a substitute for feature verification after code changes or for framework-specific debugging when a narrower skill exists. A workflow skill, not a hidden runtime: nothing executes automatically, the agent learns to debug itself before escalating to a human. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: written for coding-agent harnesses (Claude Code style runs with tool loops); in Muse it works as a diagnostic interview and method rather than automated capture, since Muse does not expose raw tool-call traces. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-agent-introspection-debugging
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-agent-introspection-debugging
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/agent-introspection-debugging/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
