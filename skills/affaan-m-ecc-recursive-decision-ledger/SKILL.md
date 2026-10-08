<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-recursive-decision-ledger
description: "Make repeated model rollouts safe and legible with Muse: an append-only decision ledger of trials..."
---

# Recursive Decision Ledger

Curated by Skill Harbor: a discipline for "Prime Gauss" style recursive prompting that keeps the useful part (repeated trials, prior memory, fresh information, explicit marks) and removes the unsafe part (pretending the loop proves certainty). Every rollout records a ledger contract: rollout id and timestamp, prior accepted winner and watchlist, fresh information ingested, search space size, model families or heuristics used, trial and effective trial counts, top candidates, decision marks, coherence marks against the prior ledger, and the promotion gate result. Candidates are marked accept, watch, reject, decay watch, or needs replay; winners are compared against prior winners; candidates are downgraded when drift, tail risk, stale data, or failed replay invalidates the previous mark. The hard rule: for trading, capital allocation, production deploys, migrations, or destructive ops, recursive confidence is not approval. Default to paper, dry-run, read-only, preview, or staged mode unless the user explicitly approves the live action and the gate supports it. Promote only when the candidate beats the prior accepted winner on the chosen metric, correctness and replay checks pass, risk limits are explicit, the evidence is durable, and the user approved the live step. Summaries lead with the decision, not the drama: "Rollout 15 complete. The prior winner still holds, but edge deteriorated 17%. Status: watch, not live." Prefer JSONL for append-only ledgers and Markdown for human...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-recursive-decision-ledger
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-recursive-decision-ledger
- Category: Agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/recursive-decision-ledger/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
