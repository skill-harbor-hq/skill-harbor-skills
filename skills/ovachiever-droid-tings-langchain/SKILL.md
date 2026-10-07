<!-- AUTO-GENERATED from the Skill Harbor catalog. Do not edit by hand. -->
---
name: ovachiever-droid-tings-langchain
description: "Short listing (license not verifiable): reference playbook for building LLM apps with LangChain —..."
---

# LangChain — agents, RAG and LLM app patterns (short listing)

Curated by Skill Harbor — short listing (the frontmatter claims MIT, but the discovery manifest records NOASSERTION, so nothing is reproduced here): @ovachiever's langchain skill, listed here with credit to its creator — a dense reference playbook for building LLM-powered applications with the LangChain framework: ReAct agents with tool calling (built in under 10 lines), RAG pipelines (document loaders, text splitters, Chroma/Pinecone/FAISS vector stores), conversation memory, structured output, parallel tool execution, streaming, and LangSmith observability, plus a LangChain-vs-LangGraph decision guide and alternatives (LlamaIndex, LangGraph, Haystack, Semantic Kernel). Honest caveats: the skill body ships an example calculator tool written as `lambda x: eval(x)` — a code-execution footgun if copied into production, so the safety check in the install prompt matters; it references third-party projects (langchain-ai/langchain) rather than redistributing them, and the framework itself is maintained upstream by LangChain AI, not by this repo's author; running real LLM features requires paid model API keys (OpenAI/Anthropic/Google) — free tiers exist but token usage is billed. Skill Harbor never reviews the code, review it yourself before use. Discovered via skills.sh.

- Listing: https://theskillharbor.com/products/ovachiever-droid-tings-langchain
- Fiche en français: https://theskillharbor.com/fr/products/ovachiever-droid-tings-langchain
- Category: AI agents
- Price: Free
- Verification: unverified
- Source repo: https://github.com/ovachiever/droid-tings/blob/master/skills/langchain/SKILL.md

## Install with Muse

1. Open the listing page above.
2. Copy the install package from the page.
3. Paste it into Muse and follow the steps there.

Installs on Skill Harbor are copy-paste into Muse, never automatic.

## Discover more builds

- Browse: https://theskillharbor.com/products
- Public search API (no key, read-only): GET https://theskillharbor.com/api/connector/search?q=<keywords>&limit=10
- MCP (POST https://theskillharbor.com/mcp): tools `search_builds`, `get_build`, `get_install`
