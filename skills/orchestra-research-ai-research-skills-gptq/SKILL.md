<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: orchestra-research-ai-research-skills-gptq
description: "Group-wise 4-bit quantization with ~2% perplexity loss, 4x memory reduction and 3-4x inference..."
---

# GPTQ post-training 4-bit quantization for LLMs: fit big models on small GPUs

Curated by Skill Harbor — @orchestra-research's GPTQ skill: the complete post-training 4-bit quantization workflow for LLMs — how group-wise quantization works (per-group scale/zero-point, Hessian-aware error minimization), the group-size trade-off table (32/128/256/1024 with memory, accuracy and speed guidance — 128 is the recommended default), three ready configs (standard 4-bit, high-accuracy 3-bit, max-accuracy 4-bit with small groups), kernel backends (ExLlamaV2 default, Marlin for Ampere+ GPUs, Triton for Linux), auto-gptq install and usage, loading pre-quantized models from HuggingFace (TheBloke's 1000+ GPTQ models), quantizing your own model with calibration data, transformers integration, QLoRA fine-tuning on a GPTQ base (a 70B model trainable on a single A100 80GB), multi-GPU deployment and CPU offloading patterns, and benchmark tables (4x memory reduction — Llama 2-70B 140GB → 35GB; 3.4-4.8x inference speedup; <2% perplexity degradation). Honest caveats: guidance plus pip-installable libraries — needs CUDA GPUs for real quantization; when to prefer AWQ or bitsandbytes is covered honestly (better accuracy on Ampere/Ada, simpler 8-bit integration); performance claims are the skill's, validate on your own hardware. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/orchestra-research-ai-research-skills-gptq
- Fiche en français: https://theskillharbor.com/fr/products/orchestra-research-ai-research-skills-gptq
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/orchestra-research/ai-research-skills/blob/main/10-optimization/gptq/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
