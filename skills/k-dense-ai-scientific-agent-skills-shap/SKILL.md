<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: k-dense-ai-scientific-agent-skills-shap
description: "Rigorous SHAP playbook for fitted models — define the explanation target, select explainer + masker..."
---

# Explain ML predictions with SHAP: explainer selection, additivity checks, honest reporting

Curated by Skill Harbor — @k-dense-ai's SHAP skill for explaining fitted machine-learning models, aligned with SHAP 0.52.0 and the modern `shap.Explanation` API: a 7-step rigorous workflow. Step 1, define the explanation target (model version, exact callable, output name/index and units, evaluation rows, background population). Step 2, select explainer and masker from a decision table (TreeExplainer, LinearExplainer, ExactExplainer, PermutationExplainer, PartitionExplainer, Deep/GradientExplainer, legacy KernelExplainer — with per-family constraints). Step 3, compute a modern Explanation with a complete binary-classification worked example. Step 4, control tree output semantics (probability/log-loss spaces need interventional masking). Step 5, use model-agnostic callables deliberately with budgeted permutation evals. Step 6, "visualize the question, not merely the available plot" — a question-to-plot mapping (beeswarm, waterfall, scatter, heatmap, text/image). Step 7, report limitations with results: baseline, explainer, masker, additivity error, correlated features, and a clear non-causal statement. Strong integrity rules throughout: never use SHAP as a substitute for predictive validation, never silence an additivity failure, never load untrusted pickle/joblib artifacts (code execution risk). Honest caveats: requires Python 3.12+ and uv for SHAP 0.52.0; SHAP describes model behavior — it does not establish causality or fairness (a small protected-feature attribution does...

- Listing: https://theskillharbor.com/products/k-dense-ai-scientific-agent-skills-shap
- Fiche en français: https://theskillharbor.com/fr/products/k-dense-ai-scientific-agent-skills-shap
- Category: Science
- Price: Free
- Verification: unverified
- Source repo: https://github.com/k-dense-ai/scientific-agent-skills/blob/main/skills/shap/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
