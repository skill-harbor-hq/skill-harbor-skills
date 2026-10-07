<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: alterlab-ieu-alterlab-academic-skills-alterlab-molfeat
description: "Turn molecules into ML-ready feature matrices with molfeat: ECFP/MACCS/MAP4 fingerprints, RDKit and..."
---

# Molfeat — molecular featurization hub

Curated by Skill Harbor — @alterlab-ieu's alterlab-molfeat skill, listed here with credit to its creator (part of the AlterLab Academic Skills suite): a complete agent reference for molecular featurization with the molfeat Python library. It covers the three-layer model — calculators (per-molecule), transformers (scikit-learn compatible, batched, parallel), and pretrained transformers (ChemBERTa, ChemGPT, MolT5, CheMeleon, Mol-JEPA) — a featurizer selection guide by use case (traditional ML, deep learning, similarity search, pharmacophore approaches), common workflows (QSAR model building, virtual screening, scikit-learn pipeline integration, comparing featurizers), performance tips (parallelization, batching, caching, float32), state save/load for reproducibility, and error handling for invalid SMILES. Refreshingly honest about molfeat 1.0 breaking changes: DGL GIN/Graphormer and protein featurizers removed, no dgl extra, Mol-JEPA weights are CC BY-NC 4.0, and MAP4 needs the separate map4 package from GitHub. Honest caveats: license listed MIT per the discovery manifest (the skill's own frontmatter reads Apache-2.0 — the manifest makes faith here); pretrained foundation-model downloads can be large and slow on first run; your molecules come from you — the skill turns them into features, it trains nothing; outputs are research-grade features for your own models. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/alterlab-ieu-alterlab-academic-skills-alterlab-molfeat
- Fiche en français: https://theskillharbor.com/fr/products/alterlab-ieu-alterlab-academic-skills-alterlab-molfeat
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/alterlab-ieu/alterlab-academic-skills/blob/main/skills/cheminformatics/alterlab-molfeat/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
