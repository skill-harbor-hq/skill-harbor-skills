<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mukul975-anthropic-cybersecurity-skills-detecting-anomalous
description: "Defensive UEBA playbook for detecting anomalous authentication patterns: brute-force and..."
---

# UEBA auth-anomaly detector — detect brute-force, spraying, and impossible travel

Curated by Skill Harbor — @mukul975's detecting-anomalous-authentication-patterns skill (frontmatter author: `mahipal`; credited to @mukul975 as the repo publisher), listed here with credit to its creator: a defensive UEBA playbook for authentication telemetry. It guides the agent through detecting anomalous authentication patterns — brute-force attacks, password spraying, credential stuffing, impossible travel and geo-velocity analysis, token misuse, and privilege abuse — with correlation rules, baseline establishment, anomaly thresholds, SIEM/SOAR integration guidance, and incident-response triage checklists. Explicitly defensive: this is detection engineering and incident response, not offensive tooling — it helps blue teams find and triage attacks, never build them; no attack payloads, no exploit code. Honest caveats: needs 90 days of authentication baseline data plus a SIEM (Splunk/Elastic/Azure Sentinel), GeoIP enrichment, and Python 3.9+ — without baseline telemetry the detection patterns have nothing to compare against; thresholds will need tuning to your environment. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mukul975-anthropic-cybersecurity-skills-detecting-anomalous-authentication-patterns
- Fiche en français: https://theskillharbor.com/fr/products/mukul975-anthropic-cybersecurity-skills-detecting-anomalous-authentication-patterns
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mukul975/anthropic-cybersecurity-skills/blob/main/skills/detecting-anomalous-authentication-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
