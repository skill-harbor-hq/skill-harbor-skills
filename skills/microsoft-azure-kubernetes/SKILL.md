<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: microsoft-azure-kubernetes
description: "Plan and create production-ready AKS clusters — Day-0 networking decisions, Automatic vs Standard..."
---

# Azure Kubernetes — Production AKS Planner

💳 Paid Azure subscription required — Curated by Skill Harbor — Microsoft's AKS planning skill: produce a recommended production cluster configuration by separating Day-0 decisions (networking model, API server access — hard to change later) from Day-1 features, choose between AKS Automatic (curated, default) and Standard (full control) SKUs, then work through networking (Azure CNI Overlay, Cilium dataplane, egress, ingress), security (Entra ID everywhere, Key Vault via Secrets Store CSI, Azure Policy), observability (Managed Prometheus, Container Insights, Grafana), upgrades, node pools and reliability (3 availability zones, PodDisruptionBudgets) — with cost controls like spot node pools and cluster stop/start for dev. By @microsoft, listed here with credit to its creator. Honest caveats: Day-0 decisions are hard to change later — get them right upfront; node VMs bill whether your pods run or not, so rightsizing and autoscaling matter. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/microsoft-azure-kubernetes
- Fiche en français: https://theskillharbor.com/fr/products/microsoft-azure-kubernetes
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/microsoft/azure-skills/blob/main/.github/plugins/azure-skills/skills/azure-kubernetes/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
