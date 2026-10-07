<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: tondevrel-scientific-agent-skills-jax
description: "A scientific-agent reference for JAX — composable transformations (grad, jit, vmap, pmap)..."
---

# JAX — autograd, JIT and XLA acceleration patterns

Curated by Skill Harbor — @tondevrel's jax skill, listed here with credit to its creator: a scientific-agent reference for JAX — Google's framework combining a NumPy-like API with composable function transformations (grad for differentiation, jit for XLA compilation, vmap for vectorization, pmap for parallelization) — covering when to use it (high-performance scientific simulations, higher-order derivatives, physics-informed ML, differentiable simulations, CPU/GPU/TPU portability), the core principles (pure functions and immutability, manual PRNG key management, XLA compilation), a quick reference (install patterns for CPU and CUDA, standard imports, the differentiate-and-JIT basic pattern), and critical do/don't rules for writing correct JAX code. Honest caveats: it's a reference playbook for the upstream google/jax project — install the actual jax/jaxlib from the official releases (match your CUDA version for GPU) and read the official docs at jax.readthedocs.io; JAX's functional discipline (pure functions, explicit random keys) is a real mental-model shift from NumPy/PyTorch — expect a learning curve; GPU/TPU acceleration is where the value is — on plain CPU, PyTorch or NumPy may be simpler. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/tondevrel-scientific-agent-skills-jax
- Fiche en français: https://theskillharbor.com/fr/products/tondevrel-scientific-agent-skills-jax
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/tondevrel/scientific-agent-skills/blob/main/skills/jax/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
