<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-ecc-council
description: "Convene a four-voice council (Architect, Skeptic, Pragmatist, Critic) for ambiguous decisions..."
---

# ECC Council

Curated by Skill Harbor: a four-voice decision council for ambiguous decisions, tradeoffs, and go/no-go calls. It comes from the ECC framework but works fully without it. The in-context Claude voice takes the Architect lens (correctness, maintainability, long-term implications) while three fresh subagents take Skeptic (premise challenge, simplification, assumption breaking), Pragmatist (shipping speed, user impact, operational reality), and Critic (edge cases, downside risk, failure modes). Each external voice receives only the decision question and compact context, never the full transcript; that is the anti-anchoring mechanism. The workflow: extract the real question, gather only the necessary context, form the Architect position first, launch the three voices in parallel with a strict prompt shape (position, reasoning, risk, one surprise, under 300 words), then synthesize with bias guardrails (never dismiss a view without explaining why, always include the strongest dissent, treat two-against-one as a real signal) into a compact, phone-scannable verdict. One round by default. From the affaan-m/ECC repository (MIT). Honest caveats: four voices means roughly four times the tokens per decision, so reserve it for genuinely ambiguous calls, not code review, implementation planning, or straight factual questions. Persist the outcome only when it changes something real. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-ecc-council
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-ecc-council
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/pi/core/skills/ecc-council/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
