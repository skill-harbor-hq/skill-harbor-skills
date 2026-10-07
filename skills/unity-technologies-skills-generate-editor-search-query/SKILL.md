<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: unity-technologies-skills-generate-editor-search-query
description: "Translate natural-language requests into Unity Search queries — assets, scene objects, references —..."
---

# Turn plain language into Unity Search queries

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @unity-technologies's official generate-editor-search-query skill — translate natural-language Unity Editor search requests into useful Unity Search queries, explain them briefly, and open the Unity Search window with the query when appropriate. It handles "find / search / locate / list / filter / look up / where is / which assets use" requests across project assets (materials, textures, prefabs, scenes, scripts, shaders, audio clips, sprites, meshes, ScriptableObjects) and scene objects/components (Cameras, Lights, Rigidbodies, Colliders, Canvas, UI, ParticleSystems, AudioSources, Animators, Terrain). Query generation rules: simplest query first, type filters (t:material, t:Light), dir: for folders, l: for labels, ref= for references, search expressions only when they clearly help (t:prefab ref={t:texture}), never invent unsupported filters, and for ambiguous-but-searchable requests pick the most likely query and state the assumption. Strictly read-only: never install packages, run menu commands, edit assets, modify scenes, delete results, or do dependency-graph analysis — if the user asks to act on results, open Search first and ask for confirmation. Opening Search runs C# in the Editor via eval (statement block, not a file: no using directives, fully-qualified types) — base64-encodes the query and opens the SearchService window, never claiming success if the command failed....

- Listing: https://theskillharbor.com/products/unity-technologies-skills-generate-editor-search-query
- Fiche en français: https://theskillharbor.com/fr/products/unity-technologies-skills-generate-editor-search-query
- Category: Game Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/unity-technologies/skills/blob/main/skills/generate-editor-search-query/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
