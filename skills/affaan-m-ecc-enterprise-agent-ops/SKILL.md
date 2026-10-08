<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-enterprise-agent-ops
description: "Run production agent fleets with Muse like real services: runtime lifecycle, observability..."
---

# Enterprise Agent Operations

Curated by Skill Harbor: operational controls for agent systems that run continuously instead of living inside a single CLI session. Four operational domains structure the work: runtime lifecycle (start, pause, stop, restart), observability (logs, metrics, traces), safety controls (least-privilege scopes, permissions, kill switches), and change management (rollout, rollback, audit). Baseline controls are non-negotiable: immutable deployment artifacts, least-privilege credentials, environment-level secret injection, hard timeout and retry budgets, and an audit log for high-risk actions. Metrics to track read like a service dashboard: success rate, mean retries per task, time to recovery, cost per successful task, failure class distribution. The incident pattern is spelled out: freeze new rollout, capture representative traces, isolate the failing route, patch with the smallest safe change, run regression plus security checks, resume gradually. Pairs with PM2 workflows, systemd services, container orchestrators, and CI/CD gates. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: this is the operations layer, not the agent logic; it assumes the baseline controls are actually in place, which on many teams they are not. A kill switch you never tested is a hope, not a control. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-enterprise-agent-ops
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-enterprise-agent-ops
- Category: DevOps
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/enterprise-agent-ops/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
