<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: alterlab-ieu-alterlab-academic-skills-alterlab-geniml
description: "Train ML models on BED-file genomic intervals with geniml: Region2Vec region embeddings, joint..."
---

# Geniml — machine learning on genomic interval data

Curated by Skill Harbor — @alterlab-ieu's alterlab-geniml skill, listed here with credit to its creator (part of the AlterLab Academic Skills suite): a complete agent reference for machine learning over genomic interval data with the geniml Python package. It covers Region2Vec (unsupervised word2vec-style embeddings of genomic regions from BED files), BEDspace (joint region + metadata embeddings via StarSpace for cross-modal search), scEmbed (single-cell ATAC-seq cell embeddings that drop into scanpy as `adata.obsm`), consensus peak-set / universe building (`build-universe` with CC/CCF/ML/HMM methods for tokenization references), and utilities (BBClient caching, BEDshift null models, embedding-quality evaluation, tokenization). Notably verified against geniml 0.8.4 — including a hard-won import-path table (subpackage `__init__` files don't re-export, so the obvious imports fail), CLI gotchas (the `bedspace search` query is positional; the StarSpace flag is literally misspelled "starsapce"), and a clear routing table: plain interval arithmetic is gtars, not geniml. Honest caveats: universe building and hard tokenization need the external `bedtools` and `uniwig` binaries; BEDspace needs StarSpace installed separately; universe quality is the whole game — bad universe, bad embeddings; your BED data comes from you. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/alterlab-ieu-alterlab-academic-skills-alterlab-geniml
- Fiche en français: https://theskillharbor.com/fr/products/alterlab-ieu-alterlab-academic-skills-alterlab-geniml
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/alterlab-ieu/alterlab-academic-skills/blob/main/skills/domain-specific/alterlab-geniml/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
