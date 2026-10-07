<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: gamedev-skills-awesome-gamedev-agent-skills-shader-programming
description: "Write game shaders from cross-engine fundamentals — the vertex→fragment pipeline, coordinate..."
---

# Cross-engine shader programming: GLSL/HLSL fundamentals and effects

Curated by Skill Harbor — @gamedev-skills's cross-engine shader programming skill: portable fundamentals taught in GLSL with HLSL equivalents — the pipeline (vertex transforms to clip space and passes UVs/normals; fragment runs per pixel and outputs color; most effects live in the fragment stage), coordinate spaces (model → world → view → clip; normals in world or view; mixing spaces is the most common bug), driving effects with UVs (0..1) and a `time` uniform, branch-light per-pixel work (`mix`/`step`/`smoothstep`/`clamp` over `if`; GPUs dislike divergent branches), and passing data via uniforms and varyings. Worked patterns: fragment basics (sample, tint, combine), frame-rate-independent scrolling UVs (`fract(uv + speed * time)`), dissolve (threshold a noise map, glow the edge band), and 3D fresnel rim light (silhouette glow from `pow(1 - dot(normal, viewDir), power)`). A pitfalls list (mixing coordinate spaces, forgetting to normalize interpolated normals, flipped V across engines, `discard` defeating early-Z on tiled mobile GPUs, mobile precision `highp` vs `mediump`, GLSL≠HLSL mappings) and a references file with the full outline, vignette and color-grading shaders plus the GLSL↔HLSL mapping table. Honest caveats: fundamentals only — the exact engine syntax and built-ins live in companion skills (`godot-shaders`) or engine docs, not bundled here; full particle VFX belongs to `unreal-niagara`; always verify visually on the target hardware (shaders that look right on...

- Listing: https://theskillharbor.com/products/gamedev-skills-awesome-gamedev-agent-skills-shader-programming
- Fiche en français: https://theskillharbor.com/fr/products/gamedev-skills-awesome-gamedev-agent-skills-shader-programming
- Category: Game Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/gamedev-skills/awesome-gamedev-agent-skills/blob/main/skills/disciplines/shader-programming/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
