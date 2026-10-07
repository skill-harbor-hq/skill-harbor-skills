<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: orchestra-research-ai-research-skills-nanogpt
description: "Train a character-level Shakespeare model on CPU in minutes, reproduce GPT-2 (124M) on OpenWebText..."
---

# nanoGPT: Karpathy's minimalist GPT implementation, from Shakespeare to GPT-2

Curated by Skill Harbor — @orchestra-research's nanoGPT skill: the agent's guide to Karpathy's educational GPT implementation — four concrete workflows: character-level Shakespeare training in ~5 minutes on CPU (prepare → train → sample, 6 layers, 384-dim embeddings), full GPT-2 (124M) reproduction on OpenWebText with multi-GPU DDP (~4 days on 8x A100), fine-tuning from OpenAI GPT-2 checkpoints on custom text, and a custom-dataset pipeline (character tokenizer → train.bin/val.bin). It documents the model config knobs, the training-speed levers (`compile=True`, bf16), common failure fixes (OOM → shrink batch/block size; slow → compile + mixed precision; poor generations → train longer, lower temperature; can't load GPT-2 weights → check `init_from` names), hardware requirements per workflow, and when to graduate to alternatives (HuggingFace Transformers for production, Megatron-LM for large-scale, LitGPT for production architectures). Honest caveats: an educational reference, GPT-2 (124M)-scale only — not a production training framework; OpenWebText preparation takes ~1 hour and the 124M run needs serious GPU time; benchmark claims are the skill's. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/orchestra-research-ai-research-skills-nanogpt
- Fiche en français: https://theskillharbor.com/fr/products/orchestra-research-ai-research-skills-nanogpt
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/orchestra-research/ai-research-skills/blob/main/01-model-architecture/nanogpt/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
