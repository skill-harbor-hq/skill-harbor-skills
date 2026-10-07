<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gordonwei-museglimmer-shim
description: "OpenAI-compatible server for Muse Glimmer on Apple Silicon, via mlx_vlm; for local runners whose..."
---

# museglimmer-shim

Curated by Skill Harbor: museglimmer-shim is a small OpenAI-compatible /v1/chat/completions server that runs Muse Glimmer on Apple Silicon. It exists because bundled MLX runtimes (like the one in LM Studio) lag behind the model: the mlx_vlm Python package on PyPI already supports Glimmer's architecture, so this project loads the model once, in-process, and serves it over a FastAPI app shaped exactly like the OpenAI Chat Completions API, including tool-calling translation, real vision input and streaming with heartbeat frames. Any OpenAI-compatible client keeps working unchanged, just pointed at a different host and port. By @GordonWei, listed here with credit to its creator. Honest caveats: Apple Silicon + Metal only, so no Linux and no Docker on macOS (no Metal GPU passthrough); a 30B model at roughly 13-15 tok/s means a large fixed system prompt routinely pushes single-request latency past 300-400 seconds, so budget client timeouts accordingly; one request at a time, a busy request gets an immediate 503 with Retry-After: 30 instead of queueing. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/gordonwei-museglimmer-shim
- Fiche en français: https://theskillharbor.com/fr/products/gordonwei-museglimmer-shim
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/GordonWei/museglimmer-shim

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
