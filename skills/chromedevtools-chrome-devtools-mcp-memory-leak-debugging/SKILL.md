<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: chromedevtools-chrome-devtools-mcp-memory-leak-debugging
description: "Find and fix JS/Node memory leaks — capture heap snapshots, compare them, walk retainers and..."
---

# Memory leak debugging with Chrome DevTools MCP

Curated by Skill Harbor — @chromedevtools's memory-leak-debugging skill: expert guidance for finding, diagnosing and fixing memory leaks in JavaScript and Node.js apps using the Chrome DevTools MCP memory tools. Core principles: prefer the MCP memory tools (never read raw `.heapsnapshot` files — they're huge and burn tokens), isolate the leak (browser vs Node), know the common culprits (detached DOM nodes, unhandled closures, globals, unremoved event listeners, unbounded caches), and close loaded snapshots (`close_heapsnapshot`) to release server memory. The workflows: 1) capturing — drive the page with page-scoped tools, repeat interactions 10 times to amplify the leak, snapshot at baseline/target/final states; 2) comparing — summary first with `get_heapsnapshot_summary`, then `compare_heapsnapshots` with detailed class diffs only for suspicious growth; 3) inspecting retainers and dominator chains (`get_heapsnapshot_retainers`, `get_heapsnapshot_retaining_paths`, `get_heapsnapshot_dominators`, duplicate strings); 4) categorized filters (`objectsRetainedByDetachedDomNodes`, `objectsRetainedByEventHandlers`, `objectsRetainedByContexts`, `objectsRetainedByConsole`). Honest caveats: the advanced memory tools only exist when the chrome-devtools-mcp server is started with the `--memoryDebugging` flag; pairs with the `chrome-devtools-cli` listing for driving the browser. Apache-2.0 licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via...

- Listing: https://theskillharbor.com/products/chromedevtools-chrome-devtools-mcp-memory-leak-debugging
- Fiche en français: https://theskillharbor.com/fr/products/chromedevtools-chrome-devtools-mcp-memory-leak-debugging
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/chromedevtools/chrome-devtools-mcp/blob/main/skills/memory-leak-debugging/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
