<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-agent-payment-x402
description: "Let AI agents pay for APIs and services themselves over the x402 protocol, with per-task budgets..."
---

# Agent Payment Execution (x402)

Curated by Skill Harbor: enable AI agents to make policy-gated payments with built-in spending controls, from a community contributor, listed here with credit to its creator. The x402 protocol extends HTTP 402 (Payment Required) into a machine-negotiable flow: when a server returns 402, the agent's payment tool negotiates the price, checks the budget, signs a transaction, and retries only inside the policy and confirmation boundary set by the orchestrator. Every payment tool call enforces a SpendingPolicy: per-task budget, per-session cumulative budget, allowlisted recipients, and rate limits. Agents hold their own keys via ERC-4337 smart accounts; the orchestrator sets policy before delegation, the agent can only spend within bounds, no pooled funds, no custodial risk. Two integration paths: agentwallet-sdk as an MCP payment server on Base (Base Sepolia is the safest development default, Base mainnet the production path), and the OKX Agent Payments Protocol on X Layer for seller-side SDKs in TypeScript, Go, Rust and Java. Pairs naturally with cost-aware pipelines and security review skills. From the affaan-m/ECC repository (MIT). Honest caveats: real money moves here; never run on mainnet without tight budgets and allowlists, start on testnet; always pin package versions because this tool manages private keys and unpinned npx installs introduce supply-chain risk; payment packages and facilitator behavior change quickly, so fetch current SDK docs before generating production...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-agent-payment-x402
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-agent-payment-x402
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/agent-payment-x402/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
