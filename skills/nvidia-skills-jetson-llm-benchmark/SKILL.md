<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: nvidia-skills-jetson-llm-benchmark
description: "Runtime-matched wrapper scripts for vLLM, llama.cpp/GGUF, and Ollama emitting the same JSON..."
---

# Jetson LLM serving benchmarks: vLLM, llama.cpp, and Ollama with comparable JSON output

Curated by Skill Harbor — @nvidia's Jetson LLM benchmark skill: reproducible serving benchmarks on Jetson hardware with structured JSON an agent can diff. It picks the wrapper matching your runtime — `bench_vllm.sh` against a running OpenAI-compatible vLLM server (concurrency sweeps), `bench_llama_cpp.sh` through the NVIDIA-AI-IOT container for local GGUF models, `bench_ollama.sh` against an Ollama daemon via its REST API — and each emits the same envelope (model, SKU, generation, L4T, container, TTFT/ITL/TPOT/throughput p50/p99, config, warnings). Warnings fire on non-max power modes, >5% background GPU use, and `tegrastats` thermal throttling; SKU facts are populated live from the device, never guessed. Includes Jetson-specific reading guidance most LLMs don't know: on Orin Nano/NX, single-stream vs concurrency-8 throughput gaps signal memory-bandwidth saturation (shrink quantization before tuning), TTFT regressions after a JetPack upgrade are usually CUDA graph cache misses (re-warm), and Thor NVFP4 numbers never mix with Orin W4A16 without a `quant` column. Honest caveats: runs ON the Jetson device only; vLLM needs an already-running server (this skill benchmarks, it doesn't serve); Ollama numbers are single-stream and not comparable to vLLM sweeps; the llama.cpp path pulls a Docker container — tell the user before running it. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/nvidia-skills-jetson-llm-benchmark
- Fiche en français: https://theskillharbor.com/fr/products/nvidia-skills-jetson-llm-benchmark
- Category: AI
- Price: Free
- Verification: unverified
- Source repo: https://github.com/nvidia/skills/blob/main/skills/jetson-llm-benchmark/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
