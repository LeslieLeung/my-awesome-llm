---
title: 自部署 LLM 模型
---

## 概述

| 方案                | 傻瓜式部署 | 支持 CPU | 有 UI 界面 | 类型     |
| ------------------- | ---------- | -------- | ---------- | -------- |
| RMKV-Runner         | Y          | Y(?)     | Y          | selfhost |
| LocalAI             | N          | Y        | N          | selfhost |
| modelscope          | Y          | Y(?)     | Y          | 托管     |
| 阿里云 PAI-EAS      | Y          | Y(?)     | Y          | 托管     |
| 腾讯云 GPU 云服务器 | N          | Y(?)     | N          | 托管     |

## selfhost 方案

### RMKV-Runner

[![josStorer/RWKV-Runner - GitHub](https://gh-card.dev/repos/josStorer/RWKV-Runner.svg)](https://github.com/josStorer/RWKV-Runner)

跟 ChatGPT 兼容的 API，支持多种显存大小，支持 macOS，有 UI 界面等。但是看起来不是特别适合生产使用。

### LocalAI

[![go-skynet/LocalAI - GitHub](https://gh-card.dev/repos/go-skynet/LocalAI.svg)](https://github.com/go-skynet/LocalAI)

比较像能投入生产使用的 selfhost 方案，部署相对较复杂。但是这个支持纯 CPU。

## 托管方案

### 魔搭社区

[首页 · 魔搭社区](https://www.modelscope.cn/)

支持部署到阿里云 PAI-EAS 或 FC，见 [文档中心 · 魔搭社区](https://www.modelscope.cn/docs/%E6%A8%A1%E5%9E%8B%E9%83%A8%E7%BD%B2%E7%AE%80%E4%BB%8B)。

### 阿里云 PAI-EAS

[LLM\_机器学习平台 PAI-阿里云帮助中心](https://help.aliyun.com/zh/pai/use-cases/llm1)

直接选择镜像和模型就能启动，直接就有 API，感觉是最傻瓜式的一款，模型也比较齐全，可以使用 huggingface 或者前面 modelscope 的模型。

### 腾讯云 GPU 云服务器

[StableDiffusion 腾讯云服务器快速部署-腾讯云开发者社区-腾讯云](https://cloud.tencent.com/developer/article/2271484)

腾讯云这方面跟进得比较慢，仅有 GPU 云服务器一款产品与此相关。不过基础镜像里面预装了 nvidia-docker 和 GPU 驱动，只需要拉一下对应的 docker 即可部署，勉强算半傻瓜式。
