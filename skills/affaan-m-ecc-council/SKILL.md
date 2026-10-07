<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-council
description: "Convene a 4-voice council (architect, skeptic, pragmatist, critic) for trade-offs and go/no-go..."
---

# Decision council: four adversarial voices for ambiguous calls

Curated by Skill Harbor — @affaan-m's four-voice decision council for ambiguous decisions, trade-offs and go/no-go calls (not for code review, task breakdown, architecture design or straightforward facts). Four lenses: the Architect (accuracy, maintainability, long-term impact), the Skeptic (challenges premises and framing, proposes the simplest credible alternative), the Pragmatist (release speed, user impact, operational reality) and the Critic (edge cases, downside risk, failure modes). The anti-anchoring mechanism: the three external voices are launched as fresh subagents with only the question and relevant context — never the full conversation transcript. The workflow: distill the decision into one explicit prompt, gather only the context that would change the answer, form the Architect's own position first (before reading the others), launch the three voices in parallel with a strict role prompt (position, reasoning, risk, one surprise), synthesize with bias guardrails (never dismiss an outside view without explanation, always include the strongest dissent, treat two-against-one as real signal), and deliver a compact scan-on-a-phone-screen verdict (positions, consensus, strongest dissent, premise check, recommendation). Includes persistence rules (only persist when the decision changes something real), multi-round follow-up guidance, and anti-patterns (using the council for code review, handing subagents the whole transcript, hiding disagreement, persisting every...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-council
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-council
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/docs/ja-JP/skills/council/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
