<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: curiositech-wedding-immortalist
description: "Turn wedding photos into an explorable 3D world"
---

# Wedding Immortalist 3D Memory Skill for Muse

Turns thousands of wedding photos and hours of footage into an immersive 3D Gaussian Splatting experience: it drives the full pipeline from ingestion (photos, video, audio) through COLMAP structure-from-motion and 3DGS training (one scene per venue space, then unified navigation), face detection and clustering (RetinaFace/MTCNN, ArcFace/AdaFace embeddings, HDBSCAN) to build a face-clustered guest roster, AI-curated best-photo selection per person with aesthetic scoring (sharpness, composition, expression, genuine-smile detection), moment detection for a theatre mode where key moments play in-scene as floating video, and a theme-adaptive web viewer whose colors, typography, and UI honor the couple's wedding aesthetic (disco, rustic, beach, modern, queer joy, cultural fusion). Discovered via skills.sh. Honest note: this is an ambitious, compute-heavy pipeline — you will need a GPU, COLMAP, and 3DGS training tooling, plus hundreds of photos and hours of footage for good results; the skill orchestrates and instructs but cannot conjure a 3D scene from a handful of snapshots; anti-patterns section (all-frames extraction, single giant scene, photographer-only sourcing) saves a lot of wasted compute. Trust Hub security checks (Socket, Snyk) pass on skills.sh. Skill Harbor never reviews the code, review it yourself before use. Not verified.

- Listing: https://theskillharbor.com/products/curiositech-wedding-immortalist
- Fiche en français: https://theskillharbor.com/fr/products/curiositech-wedding-immortalist
- Category: Photo & Video
- Price: Free
- Verification: unverified
- Source repo: https://github.com/curiositech/some_claude_skills/blob/main/.claude/skills/wedding-immortalist/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
