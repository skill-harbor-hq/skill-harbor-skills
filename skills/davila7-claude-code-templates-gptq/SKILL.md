<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: davila7-claude-code-templates-gptq
description: "Compress LLMs to 4-bit with group-wise quantization — 4× memory reduction, <2% perplexity loss..."
---

# GPTQ — post-training 4-bit quantization for LLMs with minimal accuracy loss

Curated by Skill Harbor — @davila7's gptq skill: a practical guide to GPTQ post-training quantization for running large LLMs on limited GPU memory. Covers when to use GPTQ vs AWQ vs bitsandbytes, quick start (install AutoGPTQ, load pre-quantized models from HuggingFace, quantize your own model with calibration data), group-wise quantization mechanics and the group-size trade-off table, three configs (standard 4-bit recommended, 3-bit high-compression, 4-bit maximum accuracy), kernel backends (ExLlamaV2 default-fastest, Marlin for Ampere+, Triton Linux-only), direct transformers integration, QLoRA fine-tuning (a 70B model trainable on a single A100 80GB), performance benchmarks (memory reduction per model, tokens/sec, WikiText-2 perplexity degradation <2%), common patterns (multi-GPU, CPU offloading, batch inference), and how to find pre-quantized models. Honest caveats: targets CUDA GPUs (RTX 4090, A100 class) — limited CPU/Mac utility; AutoGPTQ and backend versions move fast; model quality claims reflect the benchmarks quoted, verify on your workload. MIT licensed (frontmatter and manifest agree). Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/davila7-claude-code-templates-gptq
- Fiche en français: https://theskillharbor.com/fr/products/davila7-claude-code-templates-gptq
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/davila7/claude-code-templates/blob/main/cli-tool/components/skills/ai-research/optimization-gptq/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
