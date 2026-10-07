<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: seb1n-awesome-ai-agent-skills-model-deployment
description: "An end-to-end workflow for deploying trained ML models — model serialization (ONNX/TorchScript)..."
---

# Model Deployment — ship trained ML models as production APIs

Curated by Skill Harbor — @seb1n's model-deployment skill, listed here with credit to its creator: an end-to-end workflow that lets an agent take a trained model artifact and ship it as a production-ready service — serializing to a portable format (ONNX, TorchScript, SavedModel, joblib), building a serving API with FastAPI or Flask (health-check endpoint, Pydantic request/response validation, structured logging, meaningful HTTP errors), containerizing with a multi-stage Dockerfile, configuring Kubernetes Deployments/Services with readiness/liveness probes and a Horizontal Pod Autoscaler (or deploying serverless on Lambda/Cloud Functions/Cloud Run), and running smoke tests against the live endpoint. It also covers monitoring with Prometheus/Grafana (latency, error rates, prediction-drift metrics), model registries (MLflow, SageMaker, W&B), and redeployment strategies (blue-green, canary). Honest caveats: the workflow generates production-facing artifacts — deployment plans touch live infrastructure, so review every manifest and run the smoke tests yourself before trusting it; the code examples are solid starting points, not hardened templates (pin your dependencies, add auth); cloud resources it creates cost real money. MIT licensed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/seb1n-awesome-ai-agent-skills-model-deployment
- Fiche en français: https://theskillharbor.com/fr/products/seb1n-awesome-ai-agent-skills-model-deployment
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/seb1n/awesome-ai-agent-skills/blob/main/ai-ml-operations/model-deployment/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
