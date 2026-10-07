<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: lynx-community-skills-reactlynx-best-practices
description: "Write, review and refactor ReactLynx code for the dual-thread runtime — writing/review/refactor..."
---

# ReactLynx best practices — dual-thread React on Lynx

Curated by Skill Harbor — @lynx-community's ReactLynx best-practices skill: write, review and refactor code for ReactLynx, where React's programming model meets Lynx's dual-thread runtime. The agent first classifies the task (writing / review / refactor), inspects the code for thread-boundary markers (`lynx.getJSModule`, `NativeModules`, `runOnMainThread`, `runOnBackground`, `main-thread:*`, `'background only'`), optionally runs the bundled heuristic scanner (`ReactLynxWorkflow`), then applies nine rule documents: detect-background-only (critical), avoid-use-layout-effect (`useEffect` for background side effects, main-thread layout events for layout reads), proper-event-handlers, main-thread-scripts-guide (JSON-serializable captures, no nested MTS), component-library-packaging (type-erased dist ESM with preserved JSX), global-props-mode, code-splitting (lazy default exports + Suspense), performance-profiling (trace events, displayName), hoist-static-jsx. Refactor mode reports findings first, explains which fixes are mechanical vs judgment calls, and applies only scoped changes with auto-fixes as suggestions. Honest caveats: the bundled scanner is a lightweight heuristic — it never replaces reading the code and applying the rule docs; explicitly excludes vanilla Lynx PAPI, DevTool/CDP debugging and build config (sibling skills cover those). Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/lynx-community-skills-reactlynx-best-practices
- Fiche en français: https://theskillharbor.com/fr/products/lynx-community-skills-reactlynx-best-practices
- Category: Frontend
- Price: Free
- Verification: unverified
- Source repo: https://github.com/lynx-community/skills/blob/main/plugins/reactlynx/skills/reactlynx-best-practices/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
