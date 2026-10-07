<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mukul975-anthropic-cybersecurity-skills-detecting-dnp3-protocol
description: "Defensive security: detect anomalies in DNP3 communications used in SCADA/ICS systems — monitor..."
---

# DNP3 Protocol Anomaly Detection — IDS for SCADA/ICS energy-sector traffic

Curated by Skill Harbor — @mukul975's detecting-dnp3-protocol-anomalies skill, listed here with credit to its creator (authored by mahipal, purely defensive OT/ICS security): detect anomalies in DNP3 communications used in SCADA/ICS systems by monitoring unauthorized control commands, firmware update attempts, protocol violations, and deviations from baseline traffic. It walks the agent through building a DNP3 anomaly detector with deep packet inspection and ML approaches — analyzing DNP3 traffic on TCP port 20000 or serial links, mapping masters to outstations, tracking poll intervals and function codes, and flagging suspicious master/outstation activity — for use cases like securing energy-sector networks, investigating suspected unauthorized control commands to RTUs and substations, or deploying anomaly-based IDS with DNP3 parsing at utility substations. Mapped to MITRE ATT&CK, MITRE ATLAS, and NIST frameworks. Honest caveats: a SPECIALIZED skill — it assumes network TAP/SPAN on DNP3 segments, a baseline of normal DNP3 traffic, and a DNP3-aware sensor (Suricata or Zeek with DNP3 parser); it explicitly separates DNP3 Secure Authentication configuration into a different task; deep packet inspection on OT networks must never disrupt live traffic — passive capture only. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mukul975-anthropic-cybersecurity-skills-detecting-dnp3-protocol-anomalies
- Fiche en français: https://theskillharbor.com/fr/products/mukul975-anthropic-cybersecurity-skills-detecting-dnp3-protocol-anomalies
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mukul975/anthropic-cybersecurity-skills/blob/main/skills/detecting-dnp3-protocol-anomalies/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
