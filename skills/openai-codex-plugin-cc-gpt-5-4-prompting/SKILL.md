<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: openai-codex-plugin-cc-gpt-5-4-prompting
description: "Block-structured prompt recipe (task, output contracts, follow-through policy, verification and..."
---

# Prompting operators' guide for Codex and GPT-5.4: XML-structured contracts and recipes

Curated by Skill Harbor — @openai's gpt-5-4-prompting skill from the Codex Claude Code plugin: the operator's recipe for composing Codex/GPT-5.4 prompts — prompt like an operator, not a collaborator: one clear task per run, compact block-structured prompts with stable XML tags (`<task>`, `<structured_output_contract>`, `<default_follow_through_policy>`, `<verification_loop>`/`<completeness_contract>`, `<grounding_rules>`/`<citation_rules>`), explicit grounding and verification rules wherever unsupported guesses would hurt, better prompt contracts before raising reasoning, and a prompt-assembly checklist (define task, smallest output contract, follow-through decision, verification/grounding/safety tags where needed, strip redundancies). Covers block selection per job type (coding/debugging → verification + missing-context gating; review → grounding + dig-deeper nudge; research → research mode + citation rules; write-capable → action safety), command choice (`review`/`adversarial-review` for local git diffs, `task` for diagnosis/planning/research/implementation, `--resume-last` for deltas), and reusable blocks plus concrete recipes in `references/`. Honest caveats: this is an INTERNAL plugin skill (`user-invocable: false`) — it activates via `codex:codex-rescue`, not by direct user invocation; the referenced blocks and recipes ship with the plugin, so install it as part of the plugin bundle for full value. Apache-2.0 licensed. Skill Harbor never reviews the code, review it...

- Listing: https://theskillharbor.com/products/openai-codex-plugin-cc-gpt-5-4-prompting
- Fiche en français: https://theskillharbor.com/fr/products/openai-codex-plugin-cc-gpt-5-4-prompting
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/openai/codex-plugin-cc/blob/main/plugins/codex/skills/gpt-5-4-prompting/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
