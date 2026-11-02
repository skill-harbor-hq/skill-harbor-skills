<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: rust-port
description: "Port code to idiomatic Rust that keeps the original behavior."
---

# rust-port

The goal is the Rust a Rust developer would have written to solve the same problem, with the same observable behavior. A line-by-line transliteration, C written in Rust syntax or Python with Box<dyn Any>, compiles but keeps every problem the original had and adds the borrow checker on top. Port the behavior, not the structure.

First, understand the original before writing anything: read the code and its tests and anything that calls it; list the observable behavior, every public function, its inputs, its outputs and every way it can fail, including the quiet parts, ordering of results, tie breaking, empty input, whitespace and case handling, integer limits, and what counts as an error versus a valid edge case; note what is incidental, things the original only does because of its language, such as manual memory management, out-parameters, NULL returns, global state, fixed-size buffers, a class that exists only to group functions, or isinstance checks; and if the original has a bug or an ambiguity, keep its behavior, flag it in the porting notes, and let the user decide, since a port is not the place to silently fix things.

Second, port the tests first. Translate the original tests into Rust tests before porting the implementation, keeping one Rust test per original test, with a name that maps back to it, so a reader can check coverage. The tests are the definition of "same behavior". If the original has no tests, write characterization tests from the behavior list.

Third...

- Listing: https://theskillharbor.com/products/rust-port
- Fiche en français: https://theskillharbor.com/fr/products/rust-port
- Category: Development
- Price: Free
- Verification: unverified
- Source repo: https://github.com/morganlinton/BeautifulRust

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
