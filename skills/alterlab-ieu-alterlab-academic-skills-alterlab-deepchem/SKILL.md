<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: alterlab-ieu-alterlab-academic-skills-alterlab-deepchem
description: "Run end-to-end molecular ML with DeepChem: featurizers, MoleculeNet benchmark datasets, scaffold..."
---

# DeepChem — molecular machine learning

Curated by Skill Harbor — @alterlab-ieu's alterlab-deepchem skill, listed here with credit to its creator (part of the AlterLab Academic Skills suite): an end-to-end reference for molecular machine learning with the DeepChem library. It covers loading chemical data (SMILES CSVs, SDF files, FASTA protein sequences), molecular featurization (circular fingerprints, RDKit/Mordred descriptors, graph featurizers) with a decision tree for picking the right featurizer, data splitting done right (scaffold splitting to prevent leakage), model selection and training (sklearn wrappers, multitask regressors, GCN/GAT/AttentiveFP graph neural networks), 30+ MoleculeNet benchmark datasets with standardized splits, and transfer learning with pretrained models (ChemBERTa, and GROVER with the honest warning that DeepChem's GroverModel is not a one-line pretrained loader). Three production-ready scripts ship with it (solubility prediction, GNN training, transfer learning), plus best-practice patterns and a pitfall-to-fix catalog (leakage, GNNs underperforming fingerprints, overfitting on small data). Honest caveats: DeepChem 2.8.0 needs Python ≤ 3.11 in a dedicated environment — its pins conflict with current scientific stacks; GPU helps for GNNs; your molecules come from you — the skill is workflows and code, not data; results are research-grade predictions, not chemistry advice for real decisions. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via...

- Listing: https://theskillharbor.com/products/alterlab-ieu-alterlab-academic-skills-alterlab-deepchem
- Fiche en français: https://theskillharbor.com/fr/products/alterlab-ieu-alterlab-academic-skills-alterlab-deepchem
- Category: Data
- Price: Free
- Verification: unverified
- Source repo: https://github.com/alterlab-ieu/alterlab-academic-skills/blob/main/skills/cheminformatics/alterlab-deepchem/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
