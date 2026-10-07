<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: affaan-m-ecc-vite-patterns
description: "Vite 8+ patterns — config, plugin tables, HMR API, env and proxy, security gotchas, library mode..."
---

# Vite build-tool patterns: config, plugins, HMR, env, library mode

Curated by Skill Harbor — @affaan-m's Vite 8+ build-tool and dev-server patterns: how dev mode (native ESM, on-demand transforms) and build mode (Rolldown v7+ or Rollup v5–6 with tree-shaking, code-splitting, Oxc minification) differ; config structure with conditional configs and key option tables (root, base, envPrefix, build.outDir/minify/sourcemap); an essential-plugins table (React SWC/Babel, Vue, vite-plugin-checker — because `vite build` transpiles but never type-checks — vite-tsconfig-paths, vite-plugin-dts, vite-plugin-svgr, rollup-plugin-visualizer, vite-plugin-pwa) plus custom-plugin scaffolding with key hooks; the HMR API (`import.meta.hot`, data mutation not reassignment, all tree-shaken from production); env variables (loading order, `VITE_` client exposure, config-side usage via loadEnv); a security section (the `VITE_` prefix is not a security boundary — anything prefixed leaks into the shipped bundle; the `loadEnv('', ...)` footgun; production sourcemaps; `.gitignore` checklist); server proxy patterns; build optimization (manualChunks object/function forms, avoid barrel files, explicit import extensions, warmup clientFiles, `vite --profile` + Speedscope profiling); library mode (`build.lib`, the two gotchas — no type output, peer deps must be externalized); SSR externalization; dependency pre-bundling; and common pitfalls (dev/build CJS mismatch, stale chunk hashes, Docker `host: true`, monorepo `fs.allow`). Honest caveats: **the skill is written in...

- Listing: https://theskillharbor.com/products/affaan-m-ecc-vite-patterns
- Fiche en français: https://theskillharbor.com/fr/products/affaan-m-ecc-vite-patterns
- Category: Frontend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/affaan-m/ecc/blob/main/docs/ja-JP/skills/vite-patterns/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
