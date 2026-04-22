# OceanBase × LangChain

向量检索与混合搜索集成实战 — OceanBase 作为 LangChain VectorStore 的完整方案。

## 内容概要

1. **为什么 AI 应用需要 OceanBase** — 数据孤岛、一致性、胶水代码、运维复杂度
2. **OceanBase 向量能力一览** — VECTOR 类型、HNSW 索引、全文检索、混合搜索
3. **pyobvector SDK** — Milvus 兼容模式 + SQLAlchemy 混合模式
4. **langchain-oceanbase 集成** — OceanBaseVectorStore 初始化、文档添加、混合检索
5. **端到端 RAG 管线** — 文档摄入 → 混合检索 → 生成回答 → 评估迭代
6. **DBMS_HYBRID_SEARCH 深度解析** — 标量过滤 → 粗排 → 精排
7. **架构对比** — 经典方案 vs 专用方案 vs OceanBase 统一引擎
8. **5 分钟上手** — Docker 启动、pip install、最小 RAG 示例

## 本地预览

```bash
python -m http.server 8000
# 打开 http://localhost:8000/ob-langchain/index.html
```

## 相关链接

- [langchain-oceanbase](https://github.com/oceanbase/langchain-oceanbase)
- [pyobvector](https://github.com/oceanbase/pyobvector)
- [OceanBase](https://en.oceanbase.com)