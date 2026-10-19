<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: arekejoker-qwen21-nsfw-pose-skill-qwen21-nsfw-pose
description: "NSFW (18+): Generate nude, explicit Qwen-Image 2.1 images locally, with NSFW LoRAs and exact 3D..."
---

# NSFW (18+): Qwen21 NSFW Pose

NSFW, adults only (18+): a local pipeline for generating nude and sexually explicit photorealistic images with Qwen-Image 2.1 in ComfyUI, with exact pose control. Four routes: text to image with a mandatory NSFW LoRA and a fixed author recipe (sampler er_sde with the beta scheduler, CFG 2.5, the sample steps and portrait size, and a seven part prompt structure that spells out camera, subject, pose limb by limb, setting and lighting, skin, explicit anatomy where desired, and finish, on a boldness ladder from clothed L0 poses to nude L2 poses and cropped L3 framing), edit mode that changes the pose of an existing character image while keeping face, hair and outfit, scripted pose transfer from a textureless 3D mannequin render, and VNCCS PoseStudio for an exact pose from a 136 pose 3D library, plus custom poses made by rotating the bones of a library pose. The folder ships 148 files: SKILL.md, 10 Python scripts, 3 ComfyUI workflow graphs, 3 author prompts with their parameter files, reference images, the author sample files (nude adult originals, their metadata and their raw ComfyUI graphs), an install guide, and 55 curated poses, each a JSON file plus a preview image, to copy into ComfyUI. Everything runs locally against your own ComfyUI; there is no third party generation service.

- Listing: https://theskillharbor.com/products/arekejoker-qwen21-nsfw-pose-skill-qwen21-nsfw-pose
- Fiche en français: https://theskillharbor.com/fr/products/arekejoker-qwen21-nsfw-pose-skill-qwen21-nsfw-pose
- Category: Creative and media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/Arekejoker/qwen21-nsfw-pose-skill

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
