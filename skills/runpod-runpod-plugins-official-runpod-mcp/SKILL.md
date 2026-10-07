<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: runpod-runpod-plugins-official-runpod-mcp
description: "Drive RunPod pods, serverless endpoints, jobs, templates, volumes, registry auth, GPU catalog and..."
---

# RunPod MCP: manage GPU cloud infrastructure from your agent

💳 **Paid API required / API payante requise** — RunPod is a paid GPU cloud: compute is billed per second, and you need a RunPod account with a payment method plus an API key. Curated by Skill Harbor — @runpod's official skill for the RunPod MCP server, which exposes RunPod's control plane (the same REST API as runpodctl) as structured tool calls: pods (list, get, create, update, start, stop, restart, delete, stream logs), serverless endpoints (create, update, delete, list workers/releases, QUEUE or LOAD_BALANCER types), jobs (run, runsync, status, stream, cancel, retry, health, purge queue), Hub public catalog deployment, managed pay-per-use public endpoints, templates, network volumes, container-registry auth (including AWS ECR delegations), GPU/CPU catalog and data-center listing, and scoped billing breakdowns. Connection options: hosted MCP server (mcp.getrunpod.io) with your API key as a Bearer header, OAuth ("Sign in with Runpod", MCP-only), or local stdio via npx. The critical guidance: for multi-step jobs, read the verified golden-path sequences (runpod/golden-paths/README.md) before calling tools — tool calls are easy to issue in the wrong order — plus the MCP-vs-runpodctl decision guide (use the CLI for file transfer, SSH, doctor setup, multi-GPU priority lists and CPU endpoints, which MCP cannot create). Honest caveats: real cloud spend happens here — the delete-tool "Unexpected end of JSON input" quirk is a false alarm (204 No Content); the AI workflow is...

- Listing: https://theskillharbor.com/products/runpod-runpod-plugins-official-runpod-mcp
- Fiche en français: https://theskillharbor.com/fr/products/runpod-runpod-plugins-official-runpod-mcp
- Category: Cloud
- Price: Free
- Verification: unverified
- Source repo: https://github.com/runpod/runpod-plugins-official/blob/main/plugins/runpod/skills/runpod-mcp/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
