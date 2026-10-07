<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mgaruccio-muse-glimmer-b70
description: "vLLM-XPU + DFlash recipe pushing Muse Glimmer 30B to ~90 tok/s on a single Intel Arc Pro B70; full..."
---

# Muse Glimmer on one Arc Pro B70

Curated by Skill Harbor: a research recipe and benchmark suite that runs Meta's Muse Glimmer 30B on a single Intel Arc Pro B70 (32 GB) far above the public baseline. By switching from llama.cpp to vLLM-XPU with a GPTQ 4-bit target, XPU graphs and a quantized DFlash draft (20 speculative tokens), the author documents 89-101 tok/s greedy single-stream decode on completed-answer workloads (GSM8K, HumanEval) versus roughly 27-32 tok/s for the published llama.cpp recipes, plus a 131k-token native context profile and a concurrency sweep (840 tok/s aggregate at C96 in burst). Every number ships with its reproduction protocol, scripts, checksums and stated limits. By @mgaruccio (Mike Garuccio), listed here with credit to its creator. Honest caveats: this is a research profile, not a production-safety claim; a near-capacity forced-length six-request test produced two empty responses and that failure remains unresolved; you need the exact hardware (one Arc Pro B70, Linux with the xe driver, Docker, /dev/dri), this is not CUDA. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/mgaruccio-muse-glimmer-b70
- Fiche en français: https://theskillharbor.com/fr/products/mgaruccio-muse-glimmer-b70
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mgaruccio/muse-glimmer-b70

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
