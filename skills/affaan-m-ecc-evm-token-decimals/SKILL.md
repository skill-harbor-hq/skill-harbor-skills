<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-evm-token-decimals
description: "Never ship balances off by 10^12 again: query decimals() at runtime, cache by chain and token, use..."
---

# EVM Token Decimals Done Right

Curated by Skill Harbor: a defensive-coding guide for one of the easiest ways to silently ship wrong numbers in Web3 apps. Assuming every token uses 18 decimals, or that a stablecoin uses the same decimals on every chain, produces balances and USD values off by orders of magnitude without throwing an error. The skill lays down five rules: always query decimals() at runtime, cache by chain id plus token address (never by symbol), use Decimal, BigInt or exact integer math instead of floats, re-query decimals after bridging or wrapper changes, and normalize internal accounting consistently before any comparison or pricing. It includes working snippets for Python with web3.py, TypeScript with ethers, Solidity WAD normalization, defensive fallback handling for old tokens whose decimals() reverts, and a quick cast call to check a token on chain. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: the defensive default of 18 for reverting tokens is a guess, log it loudly when it fires; RPC calls cost latency, so the caching advice is load-bearing. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-evm-token-decimals
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-evm-token-decimals
- Category: Web3
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/evm-token-decimals/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
