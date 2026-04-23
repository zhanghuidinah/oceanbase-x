# OceanBase × Dify

One-Click Vector Store for AI App Platform — Dify + OceanBase/seekdb from deployment to RAG practice.

## Contents

1. **Dify Overview** — Visual Workflow, Agent system, Knowledge Base RAG, Plugin ecosystem
2. **Why Dify Knowledge Base Needs OceanBase** — Transactional consistency, native hybrid search, unified engine, seekdb lightweight start
3. **Architecture** — Dify platform ↔ OceanBase/seekdb ↔ LLM/Embedding/Reranker
4. **Docker Compose One-Click Deployment** — .env configuration, oceanbase/seekdb profile
5. **seekdb Lightweight AI Search Engine** — Minimal deployment, AI built-in functions, Schemaless API
6. **Dify Knowledge Base + OceanBase RAG Workflow** — Create knowledge base, upload documents, configure retrieval, orchestrate workflow
7. **Dify Plugin Marketplace** — OceanBase query plugin, MCP integration, custom tools

## Local Preview

```bash
python -m http.server 8000
# Open http://localhost:8000/ob-dify/index.html
```

## Links

- [OceanBase × Dify Docs](https://www.oceanbase.ai/docs/dify/)
- [seekdb](https://github.com/oceanbase/seekdb)
- [Dify Marketplace — OceanBase Plugin](https://marketplace.dify.ai/plugin/oceanbase/oceanbase)