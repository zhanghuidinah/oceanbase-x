<div align="center">

# OceanBase X

**Bringing the Database into AI Workflows**

[中文](https://oceanbase.github.io/ob-x/) · [English](https://oceanbase.github.io/ob-x/index_en.html)

</div>

---

OceanBase X is a presentation suite that shows how OceanBase integrates with leading AI frameworks — from vector retrieval to knowledge governance, from one-click deployment to production-grade RAG pipelines.

## Why OceanBase X?

AI workloads demand more from databases than traditional CRUD: vector search, hybrid retrieval, and knowledge management are now table stakes. OceanBase X answers one question through three end-to-end demos —

> **What can OceanBase do in AI scenarios?**

| Scenario | Directory | Highlights |
|----------|-----------|------------|
| LangChain ecosystem | `ob-langchain/` | VectorStore, hybrid search, pyobvector SDK, RAG pipeline |
| Dify platform integration | `ob-dify/` | docker-compose one-click deploy, knowledge base, vector store plugin |
| RAGFlow / PowerRAG | `ob-ragflow/` | Multi-modal retrieval, knowledge base governance |

## Viewing

**Online** (recommended)

- CN: https://oceanbase.github.io/ob-x/
- EN: https://oceanbase.github.io/ob-x/index_en.html

**Locally**

```bash
python -m http.server 8000
# then open http://localhost:8000/index_zh.html
```

You can also open any subdirectory's `index.html` (CN) or `index_en.html` (EN) directly for an individual deck.

## Design language

- **Engine**: Reveal.js 5 + Tailwind CSS + Highlight.js
- **Brand colors**: `#1a1aff` OceanBase Blue / `#00d4aa` OceanBase Teal
- **Font stack**: Inter → Noto Sans SC → JetBrains Mono
- **Theme**: `styles/ob-theme.css`

## Contributing

Copy any deck directory as a starting point and adjust theme variables in `styles/ob-theme.css`. PRs welcome.