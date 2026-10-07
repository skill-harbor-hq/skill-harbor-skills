<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: runcomfy-relight
description: "Relight still images on RunComfy — Qwen Edit relight LoRA plus Nano Banana, GPT Image 2, Flux..."
---

# RunComfy Relight

💳 Paid API required — Curated by Skill Harbor — a lighting router for stills on RunComfy: it changes a photo's direction, color temperature, intensity, or mood without reshooting — defaulting to the purpose-built Qwen Edit 2509 relight LoRA for precise lighting control (product relighting, portrait mood shifts), and falling back to identity-preserving edit endpoints when prose lighting language is enough — Nano Banana 2 Edit for composite edits or multi-image batch relight of a whole SKU gallery, GPT Image 2 Edit to match the lighting of a reference photo, FLUX Kontext Pro for surgical single-image lighting tweaks. The skill also ships a prompting discipline: lead with the lighting type, quantify color temperature (3200K warm / 5500K neutral / 6500K cool), direction, and intensity, and state preservation explicitly so the subject doesn't drift. By @genmedia-labs, listed here with credit to its creator. Requires the `runcomfy` CLI and a RunComfy account with paid generation credits — every generation is billed. Honest caveats: the CLI endpoint is image-only — video relighting lives in ComfyUI workflows on runcomfy.com and isn't reachable from this skill; multi-light setups take careful prompt phrasing to land. The skill runs shell commands (declared as `Bash(runcomfy *)`), so review what it runs. Skill Harbor never reviews the code, review it yourself before use.

- Listing: https://theskillharbor.com/products/runcomfy-relight
- Fiche en français: https://theskillharbor.com/fr/products/runcomfy-relight
- Category: Media
- Price: Free
- Verification: unverified
- Source repo: https://github.com/genmedia-labs/skills/blob/main/relight/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
