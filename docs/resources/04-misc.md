---
title: 杂项
---

## 代理

如果你身处中国大陆境内，你可能需要使用代理才能使用 OpenAI 官方的 API。注意这里仅讨论使用 OpenAI API的方式，不涉及任何关于网络的魔法。

目前最建议的使用方式是使用云服务的 Serverless，例如腾讯云或阿里云的服务，云函数地域选择境外（不可以选中国香港，推荐新加坡）即可。提供两个项目作为参考。

[easychen/openai-api-proxy](https://github.com/easychen/openai-api-proxy)

[Ice-Hazymoon/openai-scf-proxy](https://github.com/Ice-Hazymoon/openai-scf-proxy)