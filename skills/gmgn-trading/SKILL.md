<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gmgn-trading
description: "Screen Robinhood Chain meme tokens with GMGN smart-money tracking and hard insider, dev-holding and..."
---

# GMGN Trading

⚠️ **Trading warning / Avertissement trading** : informational only, not investment advice, and this is one of the highest-risk corners of crypto: meme tokens routinely go to zero within hours, screening scores cannot change that base rate, and any entry this skill informs can lose its full value. Read the safety block of the install prompt before anything else. Curated by Skill Harbor: the screening standards document of mogons' noraz-agent, an agent trading infrastructure for the Robinhood Chain (an EVM chain, ID 4663). The skill defines when a meme token may be called at all: smart-money confirmation first (at least 2 verified GMGN smart trader wallets buying the same token, fresh, with a minimum aggregate buy, plus a confidence boost when 3 or more smart-money or KOL wallets cluster), then hard risk gates fed by the GMGN OpenAPI security data: insider ratio under 30%, dev holding at most 10% or burned or renounced, top-10 holders under 40%, rug ratio under 30%, wash-trading flags rejected outright, and a token security check (honeypot, blacklist, renounced, taxes, locks) that fails closed, meaning an unavailable check is a rejection, not a pass. It also documents the API plumbing the repo implements: candidate sources from market rank, trenches and hot searches endpoints, key rotation across a pool of GMGN API keys on rate limits, and paced retries. From the mogons/noraz-agent repository (MIT, default branch master). Honest caveats: this is a standards layer for the...

- Listing: https://theskillharbor.com/products/gmgn-trading
- Fiche en français: https://theskillharbor.com/fr/products/gmgn-trading
- Category: Trading
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mogons/noraz-agent/blob/master/.agents/skills/gmgn-trading/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
