<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mattpocock-skills-chief-of-staff
description: "Pursue a long running goal in one session by coordinating subagents, with a chief of staff who..."
---

# Chief of Staff

A chief of staff for a long running goal pursued inside a single agent session. The skill makes the agent the directly responsible individual for the goal and has it think on two tracks at once: tactical (complete the immediate task) and strategic (modify the environment so the next task goes better: constrained APIs and functions, lint rules, coding standards files, data sources such as logs and test databases, and a no workarounds rule). All work is done in subagents, in the background where possible, communicating sparsely through context pointers (research notes, previous commits) instead of duplicated information, and the skill suggests recurring schedules when the harness permits. Upstream state, stated plainly: the skill lives in the repository folder skills/in-progress/, its frontmatter sets disable-model-invocation to true, and its OpenAI agent file sets allow_implicit_invocation to false, so it runs only when you invoke it explicitly. It is an in progress skill, not a finished one.

- Listing: https://theskillharbor.com/products/mattpocock-skills-chief-of-staff
- Fiche en français: https://theskillharbor.com/fr/products/mattpocock-skills-chief-of-staff
- Category: Business
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mattpocock/skills

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
