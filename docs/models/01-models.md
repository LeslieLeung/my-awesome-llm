---
title: 模型一览
---

> 更新时间：2023-05-23

列举了一些当前比较热门的模型，因篇幅有限，仅考虑对标 GPT 3.5 及以上能力的模型。

| 模型                                              | 开发公司/组织 | 公开访问 | 网页  | API | 逆向 API | 是否可联网 | 能力    | 需要自行部署[4] |
| ------------------------------------------------- | ------------- | -------- | ----- | --- | -------- | ---------- | ------- | --------------- |
| [gpt-3.5-turbo](https://openai.com/product/chatgpt)                                     | OpenAI        | ✅       | ✅    | ✅  | ✅       | ✅[2]      |         |                 |
| [gpt 4](https://openai.com/product/gpt-4)                                             | OpenAI        | ✅       |       | ✅  | ✅       | ✅[2]      |         |                 |
| [Claude](https://www.anthropic.com/index/introducing-claude)                                            | anthropic     |          |       | ✅  |          |            |         |                 |
| [Bard](https://bard.google.com/)                                              | Google        | ✅       | ✅    |     | ✅       | ✅         |         |                 |
| [文心一言](https://yiyan.baidu.com/)                                          | 百度          | ✅       | ✅    |     |          | ✅         | 作图    |                 |
| [通义千问](https://tongyi.aliyun.com/)                                          | 阿里巴巴      |          | ✅    |     |          |            |         |                 |
| Bing Chat                                         | 微软          | ✅       | ✅[1] |     |  ✅        | ✅         | 作图[3] |                 |
| [Spark](https://xinghuo.xfyun.cn/)                                             | 讯飞          |          |       | ✅  |          |            |         |                 |
| [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B) | 清华          | ✅       |       |     |          |            |         | ✅              |
| [GLM-130B](https://github.com/THUDM/GLM-130B)     | 清华          |          |       |     |          |            |         |                 |
| [MOSS](https://github.com/OpenLMLab/MOSS)         | OpenLMLab     | ✅       |       |     |          |            |         | ✅              |

> 公开访问指不需要 waitlist，注册即可访问。
> 网页指有官方的网页客户端。
> API 指官方开放 API。
> 逆向 API 指第三方根据网页等逆向开发的 API。
> 可联网指是否能通过互联网获取比模型训练时更新的知识或实时信息（如天气等）。
> 能力指对话、文本以外的能力，例如作图。

> [1]需要使用微软 Edge 浏览器。
> 
> [2]需要使用 Plugins。
> 
> [3]需要使用创意模式。
>
> [4]标记为需要自行部署的基本为开源模型，需要自己使用 GPU 部署训练好的模型并自行开发 API。需要注意，基本上 LLM 都需要工业级大显存显卡（非常见的消费级显卡）才能运行。

有部分模型暂未收录，待补充。