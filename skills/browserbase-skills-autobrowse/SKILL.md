<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: browserbase-skills-autobrowse
description: "Turn flaky browser tasks into reliable skills — an inner agent browses while the outer agent reads..."
---

# AutoBrowse — self-improving browser automation skill

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @browserbase's AutoBrowse — self-improving browser automation through the auto-research loop. An inner agent browses a site (via the `browse` CLI) while the outer agent reads the trace, forms one evidence-grounded hypothesis per iteration, and rewrites the navigation strategy (`strategy.md`) until the task passes reliably — with multi-task parallel runs via sub-agents, an optional CDP-traced mode (paired with the sibling `browser-trace` skill), and a "graduate" step that turns a converged strategy into a self-contained Claude Code skill. Entry points are flexible (`--task`, `--tasks`, `--all`, or free-form URL/instruction). Honest caveats: needs Node.js 18+, the `browse` CLI and an `ANTHROPIC_API_KEY` — every iteration burns real API calls; remote mode runs on Browserbase cloud browsers (a paid service), with optional CDP tracing via the sibling skill; the skill's frontmatter states MIT, but no LICENSE file was detected in the repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/browserbase-skills-autobrowse
- Fiche en français: https://theskillharbor.com/fr/products/browserbase-skills-autobrowse
- Category: Browser Automation
- Price: Free
- Verification: unverified
- Source repo: https://github.com/browserbase/skills/blob/main/skills/autobrowse/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
