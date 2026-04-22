# OceanBase × Dify

AI 应用平台的一键向量底座 — Dify + OceanBase/seekdb 从部署到 RAG 实战。

## 内容概要

1. **Dify 简介** — 可视化 Workflow、Agent 系统、知识库 RAG、插件生态
2. **为什么 Dify 知识库需要 OceanBase** — 事务一致性、原生混合搜索、统一引擎、seekdb 轻量起步
3. **架构图** — Dify 平台 ↔ OceanBase/seekdb ↔ LLM/Embedding/Reranker
4. **Docker Compose 一键部署** — .env 配置、oceanbase/seekdb profile
5. **seekdb 轻量级 AI 搜索引擎** — 极简部署、AI 内置函数、Schemaless API
6. **Dify 知识库 + OceanBase RAG 工作流** — 创建知识库、上传文档、配置检索、编排 Workflow
7. **Dify 插件市场** — OceanBase 查询插件、MCP 集成、自定义工具

## 本地预览

```bash
python -m http.server 8000
# 打开 http://localhost:8000/ob-dify/index.html
```

## 相关链接

- [OceanBase × Dify 文档](https://www.oceanbase.ai/docs/dify/)
- [seekdb](https://github.com/oceanbase/seekdb)
- [Dify Marketplace — OceanBase Plugin](https://marketplace.dify.ai/plugin/oceanbase/oceanbase)