<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-operator-approval-loop
description: "Approval contract for agent-drafted outbound messages: obligations, hashed drafts, epoch-keyed..."
---

# Operator Approval Loop

Curated by Skill Harbor: a contract for agents that draft messages to external counterparties, so nothing sends on the agent's own judgment and the operator stays informed internally. Every outbound draft is filed as an obligation whose status moves from drafted to approved or rejected to sent, carrying direction, counterparty, channel and an epoch timestamp. Each obligation has one draft sidecar holding the exact text, its sha256 hash, origin coordinates and priority; decisions are recorded with the operator id, a nonce and the draft epoch they were made against, and epoch rotation means re-filing a draft invalidates any decision keyed to the old epoch, so a stale approval can never release rewritten text. A durable claim reserves dispatch with at most one active claim per obligation, preventing double sends, and a delivery ledger row proves one send or notice per obligation-decision pair. A pre-draft baseline gate can refuse filings, and internal filing notices keep the operator informed. Includes a reference SQL schema for the ledger. From the affaan-m/ECC repository (MIT). Honest caveats: a workflow contract, not turnkey software; the ledger schema must be wired into your own stack. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-operator-approval-loop
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-operator-approval-loop
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/operator-approval-loop/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
