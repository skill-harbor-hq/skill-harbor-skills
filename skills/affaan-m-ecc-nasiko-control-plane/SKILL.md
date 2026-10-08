<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-nasiko-control-plane
description: "Manage the experimental Nasiko CLI lifecycle: read-only status, consent-gated install of the pinned..."
---

# Nasiko CLI Lifecycle Bridge

Curated by Skill Harbor: a lifecycle bridge for the experimental Nasiko CLI, operated through ECC. Status checks are read-only. Installation always requires explicit user consent and installs only the ECC-qualified pinned version (currently v0.1.0), with a dry-run preview first; the qualified source is the Nasiko-Labs/nasiko repository (Apache-2.0) with pinned SHA-256 digests, and a downloaded shell bootstrap script is never an acceptable substitute. Uninstall removes only a still-qualified ECC-managed binary, with a dry-run preview first. Telemetry and any sharing with Nasiko or Itô are opt-in and separately disclosed; installation is not telemetry consent. Secrets and credentials never go into command arguments, logs, or skill output. By @affaan-m, listed here with credit to its creator. From the affaan-m/ECC repository (MIT). Honest caveats: experimental alpha state. This skill manages the CLI lifecycle only; it does not operate a Nasiko control plane. Installing the CLI proves nothing about a running server, governed agents, routing, ACLs, observability, or Itô compute connectivity; report each state separately. Use the canonical Nasiko CLI directly for connection, authentication, launch, deployment, or shutdown until those verbs have their own verified contracts. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/affaan-m-ecc-nasiko-control-plane
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-nasiko-control-plane
- Category: Claude Code
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ECC/blob/main/skills/nasiko-control-plane/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
