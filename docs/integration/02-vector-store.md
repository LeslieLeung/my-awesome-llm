---
title: 向量存储
---

在有了文档之后，因为 LLM 有上下文限制（即使是 GPT 4模型最大有32K的上下文，对于很大的文档而言还是不够用），因此需要将文档索引，转换成向量。在提问时，先将问题向量化，与文档中的向量匹配，找出最适合的上下文，提供给 LLM 模型，再生成结果。因此，这里需要两个东西：向量存储（Vector Database）和向量搜索引擎（Vector Search Engine）。

目前来说开源项目使用较多的有以下两个。

## [qdrant/qdrant](https://github.com/qdrant/qdrant)

[![qdrant/qdrant - GitHub](https://gh-card.dev/repos/qdrant/qdrant.svg)](https://github.com/qdrant/qdrant)

## [chroma-core/chroma](https://github.com/chroma-core/chroma)

[![chroma-core/chroma - GitHub](https://gh-card.dev/repos/chroma-core/chroma.svg)](https://github.com/chroma-core/chroma)

更多向量搜索引擎（Vector Search Engine），可以查看 https://ossinsight.io/collections/vector-search-engine