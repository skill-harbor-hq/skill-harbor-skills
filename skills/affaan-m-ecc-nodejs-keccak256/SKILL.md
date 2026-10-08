<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-nodejs-keccak256
description: "Stop silent hashing bugs in JS/TS: Node's sha3-256 is NIST SHA3, not Ethereum Keccak-256. Use..."
---

# Node.js Keccak-256 for Ethereum

Curated by Skill Harbor: a sharp, focused rule that fixes one of the quietest bugs in Ethereum JavaScript. Node's crypto.createHash('sha3-256') implements NIST SHA3, not the Keccak-256 that Ethereum actually uses, and the two produce different outputs for the same input with no warning at all. That silently breaks function selectors, event topics, EIP-712 signatures, Merkle proofs, storage slot computation, and public-key-to-address derivation. The skill states the one rule (never use crypto sha3-256 in Ethereum contexts) and gives copyable patterns for ethers v6, viem, and web3.js: keccak256 with toUtf8Bytes, solidityPackedKeccak256, event topic ids, mapping slot derivation with AbiCoder, and address derivation from a public key. It also includes grep commands to audit a whole codebase for the bug in one pass. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: it covers hashing only, not signature verification or key management, which deserve their own review; test your hashes against a known-good vector before shipping. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-nodejs-keccak256
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-nodejs-keccak256
- Category: Web3
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/nodejs-keccak256/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
