# OceanBase × LangChain

Vector Search & Hybrid Retrieval Integration — A complete solution for using OceanBase as a LangChain VectorStore.

## Contents

1. **Why AI Apps Need OceanBase** — Data silos, consistency, glue code, operational complexity
2. **OceanBase Vector Capabilities** — VECTOR type, HNSW index, full-text search, hybrid search
3. **pyobvector SDK** — Milvus-compatible mode + SQLAlchemy hybrid mode
4. **langchain-oceanbase Integration** — OceanBaseVectorStore initialization, document ingestion, hybrid retrieval
5. **End-to-End RAG Pipeline** — Document ingestion → hybrid retrieval → answer generation → evaluation & iteration
6. **DBMS_HYBRID_SEARCH Deep Dive** — Scalar filtering → coarse ranking → fine ranking
7. **Architecture Comparison** — Classic stack vs. specialist stack vs. OceanBase unified engine
8. **Up and Running in 5 Minutes** — Docker launch, pip install, minimal RAG example

## Local Preview

```bash
python -m http.server 8000
# Open http://localhost:8000/ob-langchain/index.html
```

## Links

- [langchain-oceanbase](https://github.com/oceanbase/langchain-oceanbase)
- [pyobvector](https://github.com/oceanbase/pyobvector)
- [OceanBase](https://en.oceanbase.com)