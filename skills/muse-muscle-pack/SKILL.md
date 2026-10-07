<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: muse-muscle-pack
description: "Give your Muse a local LLM muscle: install, secure, and connect a GPU server on your own PC."
---

# Muse Muscle Pack

Your Muse is smart, but it rents its brain by the token. This pack gives it a local muscle: a large language model running on YOUR PC's GPU, reachable from anywhere through a secure tunnel.

Three prompts, used in order:

1. **Installer** — paste into your PC agent. It detects your hardware, installs llama.cpp, downloads a model sized for your VRAM, and starts an authenticated local server. Resumable after interruption, hardware-agnostic (NVIDIA / AMD / CPU), no manual troubleshooting.
2. **Secure + Tunnel** — paste into your PC agent. Adds API-key authentication, then exposes the server through a stable, named Cloudflare tunnel (no port forwarding, no static IP, no router config). Survives reboots via Windows service or Startup folder.
3. **Brain** — paste into your cloud Muse. It connects to the tunnel, verifies the API both ways, and delegates suitable work (drafting, summarizing, batch jobs) to your local model while keeping orchestration for itself.

Battle-tested on real hardware (Ryzen 5 1600 + Radeon RX 580 8 GB, ~23-35 tokens/sec, full reboot cycle verified). Every hard lesson is baked in: the prompts detect hardware themselves, verify downloads by magic bytes, enforce auth before any exposure, and recover from interruptions — you never debug alone.

- Listing: https://theskillharbor.com/products/muse-muscle-pack
- Fiche en français: https://theskillharbor.com/fr/products/muse-muscle-pack
- Category: Developer tools
- Price: Free
- Verification: verified
- Source repo: n/a

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
