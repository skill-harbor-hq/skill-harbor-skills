<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: iart-ai-whiteboard-animation
description: "A hand that draws your explainer, stroke by stroke, in sync with the narration."
---

# Whiteboard Animation Skill for Muse

VideoScribe-style "a hand draws your explainer" animations: the core mechanic animates SVG stroke-dashoffset so paths draw themselves while a marker hand tracks the exact drawing tip frame by frame via getPointAtLength — per-letter handwriting in reading order, staggered multi-stroke reveals, erase/wipe transitions between sections, and draw pacing calibrated to the voiceover (~2.3 words/sec), one element at a time, never two at once. It covers converting art into single-stroke open paths in draw order, fill-after-outline coloring, marker-hand nib calibration, and a prefers-reduced-motion fallback that shows the finished board. The deliverable is one self-contained HTML file (single master timeline, a ?t=N seek harness to freeze any moment), verified with packaged scripts that headless-screenshot mid-stroke frames to prove the hand nib sits exactly on the draw tip. Discovered via skills.sh. Honest note: the output is an animated HTML scene, not a rendered MP4 — a full narrated video needs a Remotion composition (documented as the upgrade path); artwork must be single-stroke open paths, so filled illustrations need retracing as line art. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/iart-ai-whiteboard-animation
- Fiche en français: https://theskillharbor.com/fr/products/iart-ai-whiteboard-animation
- Category: Creativity
- Price: Free
- Verification: unverified
- Source repo: https://github.com/iart-ai/explainer-video-skills/blob/main/skills/whiteboard-animation/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
