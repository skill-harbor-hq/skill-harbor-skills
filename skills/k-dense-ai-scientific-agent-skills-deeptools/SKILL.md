<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: k-dense-ai-scientific-agent-skills-deeptools
description: "Full deepTools playbook for NGS — validate files, generate workflow scripts, normalize..."
---

# deepTools NGS analysis: BAM to bigWig, QC, heatmaps and profiles for sequencing data

Curated by Skill Harbor — @k-dense-ai's deepTools skill for next-generation sequencing analysis: a complete command-level playbook for ChIP-seq, RNA-seq, ATAC-seq and MNase-seq. Convert BAM alignments to normalized coverage tracks (bamCoverage), run QC (plotFingerprint, multiBamSummary correlation, plotPCA), compare samples (bamCompare with log2 normalization), and build heatmaps and profile plots around genomic features (computeMatrix → plotHeatmap/plotProfile). Includes a normalization-method selection guide (RPGC, CPM, RPKM, BPM — when each is valid), effective-genome-size tables for common organisms, best-practice rules (validate files first, never extend reads for RNA-seq, always for ChIP-seq), and two helper scripts: validate_files.py for input checking and a workflow generator that scaffolds full bash pipelines (chipseq_qc, chipseq_analysis, rnaseq_coverage, atacseq). Honest caveats: tooling plus methodology — deepTools must be installed (uv pip or conda/bioconda, especially on shared HPC) and you need real sequencing data (BAM/BED/bigWig); the bundled commands assume command-line workflows; the skill asks that substantial use be cited in manuscripts (arXiv:2609.00065). MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/k-dense-ai-scientific-agent-skills-deeptools
- Fiche en français: https://theskillharbor.com/fr/products/k-dense-ai-scientific-agent-skills-deeptools
- Category: Science
- Price: Free
- Verification: unverified
- Source repo: https://github.com/k-dense-ai/scientific-agent-skills/blob/main/skills/deeptools/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
