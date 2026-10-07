<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: runcomfy-controlnet-pose
description: "Pose-conditioned image and video generation on RunComfy — Kling Motion Control, Wan Animate..."
---

# RunComfy ControlNet Pose

💳 Paid API required — Curated by Skill Harbor — an intent router for pose-conditioned generation on RunComfy: it classifies the request (video motion transfer vs still-image pose conditioning, stylized vs photoreal) and picks the right endpoint — Kling 2-6 Motion Control Pro or Standard to transfer a reference video's motion and blocking onto a target character, community Wan 2-2 Animate for audio-driven stylized character animation with pose conditioning, and Z-Image Turbo ControlNet LoRA for pose-locked image generation from an OpenPose / DWPose / canny / depth control image. For multi-condition stacks (pose + depth + reference), it points the agent at the full ComfyUI workflows on runcomfy.com instead, since those aren't reachable through the CLI. By @genmedia-labs, listed here with credit to its creator. Requires the `runcomfy` CLI and a RunComfy account with paid generation credits — every generation is billed. The skill executes shell commands through the CLI (declared as `Bash(runcomfy *)`), so review what it runs; reference video and control-image URLs are treated as untrusted, so only feed it assets you supplied. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/runcomfy-controlnet-pose
- Fiche en français: https://theskillharbor.com/fr/products/runcomfy-controlnet-pose
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/genmedia-labs/skills/blob/main/controlnet-pose/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
