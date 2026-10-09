<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pm-data-discovery
description: "Find prediction markets, inspect what data exists, and save research samples to files, before any..."
---

# PM Data Discovery

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice. This skill collects data and places no trades at all; data alone is not an edge, and a recorded sample describes one stretch of one market, not its future behaviour. Curated by Skill Harbor: the data-discovery runbook of oracle3, the open-source prediction-market engine and MCP server. It answers three questions before any strategy work: which data sources are available, how to find the target markets, and how to save the data as files that later research can use. Online, it lists, searches and inspects markets on Polymarket and Kalshi (metadata, history), fetches news from Google and RSS sources, and records raw event streams to JSONL files; offline, it works from local history files with research commands that sort markets and cut slices by market and event. The same ground is reachable through the MCP server's search, market, order book and quote tools. Every output is a data inventory (markets, time range, file paths) with the exact command that reproduces it, and the flow falls back to the local commands when the network is unavailable instead of stopping. The boundary is stated in the skill itself: discover, filter, sample and save only; no strategy hypotheses belong here. From the YichengYang-Ethan/oracle3-prediction-market-agent repository (Apache-2.0). Honest caveats: venue data quality and history depth vary, a recorded stream is a sample with gaps rather than a complete...

- Listing: https://theskillharbor.com/products/pm-data-discovery
- Fiche en français: https://theskillharbor.com/fr/products/pm-data-discovery
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/YichengYang-Ethan/oracle3-prediction-market-agent/blob/main/skills/pm-data-discovery/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
