<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-defi-amm-security
description: "Audit Solidity AMMs with Muse: reentrancy and CEI ordering, donation/inflation attacks, TWAP..."
---

# DeFi AMM Security Checklist

Curated by Skill Harbor: a security checklist plus hardened patterns for Solidity AMM contracts, liquidity pools, and swap flows. It walks through the classic failure modes with vulnerable-versus-safe code: reentrancy fixed by checks-effects-interactions ordering plus ReentrancyGuard and SafeERC20 instead of hand-rolled guards; donation or inflation attacks fixed by tracking internal _totalAssets and measuring actual tokens received instead of trusting balanceOf(address(this)); oracle manipulation fixed by reading TWAP instead of flash-loan-manipulable spot prices; missing slippage protection fixed by requiring caller-provided amountOutMin and deadline on every swap; overflow-prone reserve math fixed with FullMath.mulDiv; and admin functions gated behind Ownable2Step with an emergency pause that is actually tested. A closing checklist turns it into a review pass, with slither, echidna, and forge fuzzing as the recommended tooling. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a checklist is not a professional audit, get one before mainnet; never paste private keys, seed phrases or mainnet signing credentials into a chat while using it; ask before running long fuzzing jobs that consume significant local or paid resources. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-defi-amm-security
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-defi-amm-security
- Category: DeFi
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/defi-amm-security/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
