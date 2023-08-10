---
title: 杂项
---

## Key 中间商

整理了两个，有 aff，介意的可以去掉。

| 来源     | 价格                                | 倍率 |
| -------- | ----------------------------------- | ---- | 
| 官方     | 0.002 USD（~0.014 CNY） / 1K tokens | 1    |
| [AI Proxy](https://aiproxy.io/?i=leslieleung) | 0.02 CNY / 1K tokens                | 1.43 |
| [API2D](https://api2d.com/r/197314)    | 0.021 CNY / 1K tokens               | 1.5  |

## 代理

如果你身处中国大陆境内，你可能需要使用代理才能使用 OpenAI 官方的 API。注意这里仅讨论使用 OpenAI API的方式，不涉及任何关于网络的魔法。

目前最建议的使用方式是使用云服务的 Serverless，例如腾讯云或阿里云的服务，云函数地域选择境外（不可以选中国香港，推荐新加坡）即可。提供两个项目作为参考。

[easychen/openai-api-proxy](https://github.com/easychen/openai-api-proxy)

[Ice-Hazymoon/openai-scf-proxy](https://github.com/Ice-Hazymoon/openai-scf-proxy)

我自己目前在使用以下这一个，可以很方便分发 key 给家人朋友，也方便管理用量。

[songquanpeng/one-api](https://github.com/songquanpeng/one-api)