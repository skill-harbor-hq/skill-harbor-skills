<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: jiangmuran-claude-image
description: "Teach your coding agent to generate and edit images with gpt-image-2: prompt grammar, exact text..."
---

# gpt-image-2

💳 Paid API required. Curated by Skill Harbor: this is the skill from the claude-image repo, and it teaches a coding agent to generate, edit, and iterate on images with the gpt-image-2 model. It covers the prompt grammar (open with intent, quote every text string exactly, one style anchor, no magic words), a zero-dependency CLI (scripts/gpt_image.py) that handles auth, retries, parallel batching, and file IO, precise local edits via a change-ONLY-X / preserve-Y-exactly pattern, mask-based inpainting, a size table per use case, and a strict visual self-verification loop: the agent reads each PNG itself and checks text rendering, composition, and style before showing it to you. By @jiangmuran, listed here with credit to its creator. Discovered via github.com/topics/ai-skills. Honest caveats: needs a paid API key for gpt-image-2; the default API host in the repo is a third-party proxy (jmrai.net), you can override it with your own OpenAI-compatible host; the host does not support multi-image input or transparent backgrounds; this skill is built for coding agents with shell access in the Claude Code style, not for chat-only assistants; the repo includes a few Chinese examples. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/jiangmuran-claude-image
- Fiche en français: https://theskillharbor.com/fr/products/jiangmuran-claude-image
- Category: Image Generation
- Price: Free
- Verification: unverified
- Source repo: https://github.com/jiangmuran/claude-image

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
