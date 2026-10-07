<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mukul975-anthropic-cybersecurity-skills-detecting-deepfake
description: "Defensive security: detect AI-generated deepfake audio used in voice phishing (vishing) — extract..."
---

# Deepfake Audio Detection — spot AI-cloned voices in vishing attacks

Curated by Skill Harbor — @mukul975's detecting-deepfake-audio-in-vishing-attacks skill, listed here with credit to its creator (authored by mukul975, purely defensive fraud/soc work): detect AI-generated deepfake audio used in voice phishing by extracting spectral features (MFCC, spectral centroid, spectral contrast, zero-crossing rate) and classifying samples with machine learning models. It ships the full workflow — audio preprocessing (resample, trim, normalize with librosa), feature extraction, batch audio analysis, confidence scoring, and forensic reporting — for use cases like investigating a suspected AI-cloned executive voice authorizing a wire transfer, validating a voicemail that sounds like the CEO but feels off, or giving blue teams detection capability against red-team voice cloning. Mapped to MITRE ATT&CK, MITRE ATLAS, D3FEND, and NIST frameworks. Honest caveats: detection models are only as good as their training data — a reference corpus of genuine voice samples improves accuracy; deepfake generators improve constantly, so detection is an arms race; audio evidence needs proper chain of custody for legal use. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mukul975-anthropic-cybersecurity-skills-detecting-deepfake-audio-in-vishing-attacks
- Fiche en français: https://theskillharbor.com/fr/products/mukul975-anthropic-cybersecurity-skills-detecting-deepfake-audio-in-vishing-attacks
- Category: Security
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mukul975/anthropic-cybersecurity-skills/blob/main/skills/detecting-deepfake-audio-in-vishing-attacks/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
