<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-kubernetes-patterns
description: "Production Kubernetes patterns: manifests, resource limits, probes, RBAC, autoscaling..."
---

# Kubernetes Patterns

Curated by Skill Harbor: a patterns skill for writing, reviewing, and debugging Kubernetes workloads the way production teams do. It covers the full manifest surface: Deployments, Services, Ingress, and Jobs written correctly; resource requests and limits that prevent noisy-neighbor failures; liveness and readiness probes tuned to real startup behavior; RBAC roles, namespaces, and ServiceAccounts with least privilege; ConfigMap and Secret handling without leaking credentials; Horizontal Pod Autoscalers and PodDisruptionBudgets for resilient scaling; and a kubectl debugging playbook for the classic failure modes (CrashLoopBackOff, OOMKilled, pending pods, image pull errors). Every pattern is concrete YAML-level guidance, not theory. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: pure guidance, nothing to install; assumes access to a Kubernetes cluster and YAML basics; always review manifests before applying to a real cluster. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-kubernetes-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-kubernetes-patterns
- Category: Kubernetes
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/kubernetes-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
