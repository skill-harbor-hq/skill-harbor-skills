<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: pytorch-pytorch-docstring
description: "Write PyTorch-style docstrings — raw strings, Sphinx/reST, signature-first-line, math directives..."
---

# PyTorch docstring conventions: write function and method docstrings the PyTorch way (short listing)

Selected by Skill Harbor — short listing (the repo states no license, so no content is reproduced): @pytorch's official docstring-writing guide for the PyTorch project. The conventions: raw strings (`r"""..."""`), Sphinx/reStructuredText format, function signature as the first line (parameters, defaults, return type, no trailing period), one-line brief description, math via Sphinx directives (`.. math::` and inline `:math:`), cross-references with roles (`:class:`, `:func:`, `:meth:`, `:attr:`, `:ref:`), notes/warnings admonitions, Args section (lowercase name, type in parens, Default for optionals, double backticks for code), optional Keyword args section, Returns section, Examples section (always include examples with `>>>` prompts), external reference links, and method-type variants (native Python functions, C-bound via `_add_docstr`, in-place variants referencing the original, aliases), plus common patterns (LaTeX shape docs, reusable argument definitions, template insertion), a complete gumbel_softmax worked example, and a quick checklist. Honest caveats: written for contributors to the PyTorch codebase itself — the conventions transfer to any Sphinx-documented Python project, but the examples and templates are PyTorch-specific; license not stated by the source repo — short listing with a link only, nothing copied. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/pytorch-pytorch-docstring
- Fiche en français: https://theskillharbor.com/fr/products/pytorch-pytorch-docstring
- Category: Developer tools
- Price: Free
- Verification: unverified
- Source repo: https://github.com/pytorch/pytorch/blob/main/.claude/skills/docstring/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
