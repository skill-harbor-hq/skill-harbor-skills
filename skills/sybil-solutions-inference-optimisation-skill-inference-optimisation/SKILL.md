<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: sybil-solutions-inference-optimisation-skill-inference
description: "Curated by Skill Harbor: Hill-climbs your local LLM server speed, decode, prefill and startup, with..."
---

# Inference Optimisation Skill

Curated by Skill Harbor: Hill-climbs the serving speed of a local LLM server on any hardware and any quantization, from decode and prefill to KV cache, startup time and time to first token. It computes the theoretical ceiling first, then runs noise-controlled A/B experiments, one change at a time, and keeps a ledger of every run.

It works with vLLM, SGLang, llama.cpp, ExLlama and TabbyAPI, MLX and TensorRT-LLM, and climbs through the cheapest levers first: persistent caches, decode graphs, speculative decoding, concurrency and KV sizing, then prefill tuning and kernel sizes. Its ground rules are strict: one change per experiment, at least six decode samples per run, controls on both sides, and a win counts only if it beats both controls and regresses nothing by more than about three percent. It also enforces one GPU job at a time, a fixed power profile and a memory cap watchdog, and it forbids printing or copying any credential. Run-to-run noise is typically five to ten percent, so small gains may be noise, and results depend on your hardware, model and quantization. Some trades are labelled lossy, such as int8 prefill, and a server must never be force-killed mid-batch. By @sybil-solutions, listed here with credit to its creator. Discovered via GitHub. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/sybil-solutions-inference-optimisation-skill-inference-optimisation
- Fiche en français: https://theskillharbor.com/fr/products/sybil-solutions-inference-optimisation-skill-inference-optimisation
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/sybil-solutions/inference-optimisation-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
