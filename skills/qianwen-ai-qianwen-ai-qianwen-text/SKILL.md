<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: qianwen-ai-qianwen-ai-qianwen-text
description: "Chat, code and function-call with Qwen models through the OpenAI-compatible API"
---

# Qwen text chat: OpenAI-compatible API skill

Curated by Skill Harbor — @qianwen-ai's Qwen text skill: generate text, hold conversations, write code, reason and call functions through the OpenAI-compatible chat/completions API with a bundled stdlib-only Python script (`scripts/text.py` — streaming, `--output` save, `--print-response`), three fallback paths (curl, Python SDK, autonomous resolution), function calling, structured JSON output, web search, thinking mode, batch inference with a 50% discount, plus API-key type detection (PAYG vs Token Plan — Token Plan keys only allow listed models) and strict key hygiene (never output API keys in plaintext; guide the user to set DASHSCOPE_API_KEY in `.env` instead of asking for the key directly). Requires Python 3.9+ and a QianWen/DashScope API key — free-tier quota exists (check the qianwen-usage skill). Includes a diagnostic table for common failures (401, 429, SSL, proxy), mandatory post-execution stderr signal checks (`[ACTION_REQUIRED]`, `[UPDATE_AVAILABLE]`) that surface update notices, and detailed references (execution, API, prompt engineering, sources). Honest caveats: the model catalogs are point-in-time snapshots — verify the model ID against the official list before committing; output files always go to `./output/` under the working directory, never into the skill's own folder; Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/qianwen-ai-qianwen-ai-qianwen-text
- Fiche en français: https://theskillharbor.com/fr/products/qianwen-ai-qianwen-ai-qianwen-text
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/qianwen-ai/qianwen-ai/blob/main/skills/text/qianwen-text/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
