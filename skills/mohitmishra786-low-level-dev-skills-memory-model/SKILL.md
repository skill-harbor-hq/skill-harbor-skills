<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: mohitmishra786-low-level-dev-skills-memory-model
description: "Relaxed/acquire-release/acq-rel/seq-cst comparison table with C++ and Rust equivalents..."
---

# C++ and Rust memory model: atomics, orderings, and lock-free patterns

Curated by Skill Harbor — @mohitmishra786's memory-model skill: the agent's guide through the C++ and Rust memory models — the full ordering ladder (Relaxed < Release/Acquire < AcqRel < SeqCst) with C++ and Rust equivalents per rung and what each guarantees, acquire-release publish/subscribe reasoning with a worked producer/consumer example, a decision tree for picking the right ordering per use case (counters → Relaxed, refcounts → AcqRel, publish → Release/Acquire, lock-free queues → start with SeqCst), ready-to-study patterns (spinlock, reference counting, one-time lazy init), fences as ordering without a specific variable, Rust atomics (`Ordering::Relaxed`/`Acquire`/`Release`), and a common-mistakes table (Relaxed for publish/subscribe, SeqCst everywhere without profiling, `volatile` as thread-safety in C++). Cross-references companion skills for sanitizers (TSan, Miri), x86 assembly, and GDB. Honest caveats: guidance only — it does not replace testing with ThreadSanitizer on your actual target CPU; lock-free code still needs stress tests on the hardware you ship. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/mohitmishra786-low-level-dev-skills-memory-model
- Fiche en français: https://theskillharbor.com/fr/products/mohitmishra786-low-level-dev-skills-memory-model
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/mohitmishra786/low-level-dev-skills/blob/main/skills/low-level-programming/memory-model/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
