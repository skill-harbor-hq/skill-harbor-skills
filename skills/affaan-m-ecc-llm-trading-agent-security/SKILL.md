<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-llm-trading-agent-security
description: "Security patterns for autonomous trading agents: injection defense, spend limits, pre-send..."
---

# LLM Trading Agent Security

Curated by Skill Harbor: a layered security playbook for autonomous trading agents that hold wallet or transaction authority, where a prompt injection or a bad tool path can turn directly into asset loss. Treats prompt hygiene, spend policy, simulation, execution limits, and wallet isolation as independent controls, because no single check is enough. Includes concrete patterns: sanitizing on-chain data before it enters the LLM context, hard per-transaction and daily spend limits enforced outside the model, simulating every transaction before sending with a mandatory min_amount_out, circuit breakers that halt on consecutive losses or drawdown, dedicated hot wallets funded with session money only (never the primary treasury), private mempool routing, and per-strategy slippage and deadlines. Ends with a pre-deploy checklist covering sanitization, limits, simulation, breakers, key handling, and audit logging. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: a checklist and pattern library, not a security audit; patterns are starting points, not guarantees. Real money is at stake: test on testnet first, keep keys in a secret manager, and never paste seed phrases into any chat. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-llm-trading-agent-security
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-llm-trading-agent-security
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/llm-trading-agent-security/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
