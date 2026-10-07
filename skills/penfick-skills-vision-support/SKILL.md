<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: penfick-skills-vision-support
description: "A Node CLI routing screenshots and images through a configurable vision model with multi-model..."
---

# Vision bridge for text-only models: give any LLM image-reading via a CLI and a vision provider

Curated by Skill Harbor — @penfick's vision-support skill: a bridge that gives image-reading to text-only models (when the main model can't see images, a user sends a screenshot, or "look at this picture" comes up) — a Node CLI (`node vision.mjs`) with a 3-step interactive setup (pick provider, enter API key or env var name, pick model from the live list), a broad provider menu (OpenAI, Gemini, Claude, DeepSeek, Groq, Mistral, Grok, OpenRouter, Fireworks; Qwen VL, GLM-4V, Kimi, Step, MiniMax, SiliconFlow, MiMo; Ollama and LM Studio for local; any OpenAI-compatible custom endpoint), and automatic multi-model fallback — the primary model first, the rest in order on failure. Iron rule: configured vision models ONLY describe image content, never participate in the main reasoning. Commands cover single and multi-image reads, image discovery, and config management (add/edit/remove/test connectivity), with env-var overrides (`VISION_CONFIG_PATH`, `VISION_DEFAULT_MODEL`, `VISION_API_KEY`). Honest caveats: provider keys live in a local config — keep them out of prompts and logs (use env vars where possible); a paid vision-provider key may be needed unless you use a local model (Ollama/LM Studio run free locally); the SKILL.md documentation is written in Chinese. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/penfick-skills-vision-support
- Fiche en français: https://theskillharbor.com/fr/products/penfick-skills-vision-support
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/penfick/skills/blob/master/vision-support/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
