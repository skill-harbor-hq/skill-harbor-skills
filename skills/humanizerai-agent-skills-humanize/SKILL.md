<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: humanizerai-agent-skills-humanize
description: "Send text to the HumanizerAI API (light/medium/aggressive intensity) to rewrite AI-generated..."
---

# Humanize AI text via HumanizerAI API — detector-evasion rewrites (paid)

💳 Paid API required. Curated by Skill Harbor — @humanizerai's skill wiring an agent to the HumanizerAI API: invoke `/humanize` with text and an optional intensity flag (light for subtle style-preserving tweaks, medium default, aggressive for maximum bypass mode), the agent POSTs to `humanizerai.com/api/v1/humanize` and presents the humanized text with before/after scores, word count, and remaining credits. Pricing is 1 word = 1 credit, detection checks are free, and the skill covers error handling (insufficient credits, invalid key, rate limits). MIT-licensed. Honest caveats: ⚠️ dual-use by design — it explicitly lists academic detectors (Turnitin) among the targets to bypass, so consider your institution's academic-integrity rules before using it on graded work; you need your own HumanizerAI account, API key and paid credits (no free tier described) — save the key in the vault, never paste it into chat; quality claims (scores, bypass rates) are the vendor's, not ours. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/humanizerai-agent-skills-humanize
- Fiche en français: https://theskillharbor.com/fr/products/humanizerai-agent-skills-humanize
- Category: Writing
- Price: Free
- Verification: unverified
- Source repo: https://github.com/humanizerai/agent-skills/blob/main/skills/humanize/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
