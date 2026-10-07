<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: likaku-mck-ppt-design-skill
description: "Consultant-grade PowerPoint decks from a five-stage pipeline with machine-readable quality gates."
---

# McKinsey-Style PPT Designer

Curated by Skill Harbor: a skill that makes an agent build consultant-grade PowerPoint decks instead of drawing them by hand. Its engine, MckEngine (a python-pptx wrapper), exposes 67 high-level methods across 12 categories (structure, data, frameworks, comparison, narrative, timeline, team, charts, images, advanced viz, dashboards, visual storytelling) with consistent typography, overflow guard rails, and native circular chart shapes for donuts, pies, and gauges. The signature discipline is a five-stage pipeline (brief, outline, content, render plus QA, deliver) with machine-readable quality gates: the content and render gates pass only when the bundled gate_check scripts return a JSON verdict, and the skill's own anti-patterns section is explicit that a gate is never passed by the agent's say-so. It also learns: pattern-level fixes get written into an experiences/ log for future decks, and a fast track skips gates for tiny decks. By @likaku, listed here with credit to its creator. Honest caveats: much of the in-repo documentation is written in Chinese (the engine API and gate scripts work regardless, but expect to translate the brief); the example paths assume a ~/.workbuddy/skills layout you will want to adapt; and AI-generated cover images use Tencent's Hunyuan 2.0, a paid API, which is optional, the deck renders fine without it. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/likaku-mck-ppt-design-skill
- Fiche en français: https://theskillharbor.com/fr/products/likaku-mck-ppt-design-skill
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/likaku/Mck-ppt-design-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
