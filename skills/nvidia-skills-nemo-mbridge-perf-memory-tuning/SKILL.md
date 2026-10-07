<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: nvidia-skills-nemo-mbridge-perf-memory-tuning
description: "Reduce peak GPU memory in Megatron Bridge training — expandable segments, PEFT input re-gather..."
---

# Megatron Bridge GPU memory tuning: OOM fixes, fragmentation and PEFT tricks

Curated by Skill Harbor — @nvidia's GPU memory-tuning skill for Megatron Bridge: a decision-first playbook for training OOMs, starting from the finding that most OOMs are memory fragmentation, not raw capacity. The single most effective fix: `PYTORCH_CUDA_ALLOC_CONF=expandable_segments:True` (zero throughput cost). Then, in order: for LoRA with sequence parallelism, enable `sequence_parallel_input_regather` to stop retaining full gathered LoRA-A inputs; add selective activation recompute (`recompute_modules=[core_attn]`) with its ~16% utilization cost; resize parallelism (with warnings — doubling TP costs -28% throughput on Llama3 70B, raising PP costs ~6% and CPU offloading is blocked when PP > 1); the skill includes measured strategy comparisons on Llama3 70B SFT (32x H100 80GB), PEFT+SP input re-gather results (Qwen3-8B, Qwen3-30B-A3B, GPT-OSS-120B), compatibility constraints (expandable segments incompatible with `--use-nccl-ub`, CUDA-graph rules), code anchors, a failure-diagnosis table and a verification procedure with pytest commands. Honest caveats: deeply specialized — NVIDIA Megatron Bridge / NeMo distributed training on multi-GPU clusters only, not for single-GPU hobby training; references companion skills (activation recompute, FSDP) and docs in the same repo that are not bundled here. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/nvidia-skills-nemo-mbridge-perf-memory-tuning
- Fiche en français: https://theskillharbor.com/fr/products/nvidia-skills-nemo-mbridge-perf-memory-tuning
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/nvidia/skills/blob/main/skills/nemo-mbridge-perf-memory-tuning/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
