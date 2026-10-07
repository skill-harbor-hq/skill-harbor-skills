<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: agentspace-so-agent-skills-gpt-image-2
description: "💳 Paid subscription required — generate images with GPT Image 2 inside Claude Code through the..."
---

# GPT Image 2 — image generation through your ChatGPT subscription

Curated by Skill Harbor — @agentspace-so's gpt-image-2 skill, listed here with credit to its creator: generate images with GPT Image 2 (ChatGPT Images 2.0) inside your agent, through your existing ChatGPT Plus or Pro subscription — no separate OpenAI access, no per-image billing. A single bash script runs `codex exec` with the right flags, then extracts the generated image from the persisted session rollout: text-to-image, image-to-image editing, style transfer, and multi-reference composition, with the user's prompt passed through raw (no rewriting, no silent fallbacks to other models or mockups). It documents the hard constraints honestly — the local `codex` CLI must be installed and logged in with a ChatGPT plan that carries the image-generation entitlement; `--enable image_generation` is required; `--ephemeral` must not be used — plus exit codes, a careful data-handling story (only session files created by its own run are read; no other Codex conversations are touched; no telemetry), and a browser-based fallback (RunComfy) if you lack the subscription. Honest caveats: 💳 requires a paid ChatGPT Plus/Pro subscription with image entitlement and the local Codex CLI logged in — there is no free tier and nothing here works without it; one call per invocation (serialized); generation quality is whatever OpenAI's model returns. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/agentspace-so-agent-skills-gpt-image-2
- Fiche en français: https://theskillharbor.com/fr/products/agentspace-so-agent-skills-gpt-image-2
- Category: Design
- Price: Free
- Verification: unverified
- Source repo: https://github.com/agentspace-so/agent-skills/blob/main/gpt-image-2/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
