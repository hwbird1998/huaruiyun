# 开发者必看：ChatGPT API 额度、Token 和价格详解

ChatGPT 不仅通过官网 https://ai.com 向普通用户提供 Web 端服务，还为开发者开放了 API 接口，满足个性化开发需求。许多国内无需梯子即可访问的 AI 聊天机器人，正是开发者利用 ChatGPT API 实现的。

## ChatGPT API 额度说明

ChatGPT 账号默认会分配一定的 API 调用额度，通常为 5 美元（部分新账号可能为 18 美元）。对于普通用户来说，官网使用是免费的，不会消耗额度；但如果想将 ChatGPT API 集成到公众号或产品中，就需要关注额度问题。

登录 OpenAI 账号 [Usage 页面](https://platform.openai.com/account/usage) 可查看剩余额度：

![API 额度查询](https://bbtdd.com/img/78592354762.webp)

在左侧点击 "Usage"，可以查看每日消耗费用和总使用量。需要注意的是，赠送的额度有有效期，到期后会自动清零。如果后续仍需使用 API 服务，需要额外购买。

---

## 如何申请更多 API 额度

申请更多额度无需升级到 Plus 账号，只需绑定一张国外信用卡即可。你甚至可以用以下方法快速获取一张虚拟信用卡：

- 确保卡内有几美元余额。
- 根据需求选择个人或企业类型。

![绑定信用卡](https://bbtdd.com/img/776320872.webp)

绑定后，信用卡会预扣 5 美元，同时你的 GPT 账号会获得 120 美元的使用额度。注意，这不是赠送的余额，而是当月可消费的最大限额，实际扣款会在月底根据使用量从信用卡扣除。

![额度增加](https://bbtdd.com/img/168571395.webp)

如果 120 美元不够用，还可以申请更高限额，填写表格并等待审核即可。

---

## Token 是什么？

Token 是 GPT 处理文本的基本单位，可以是一个字、一个词语或特定语言中的一个字符。它将输入的文本转换为 GPT 可处理的数据格式。

- 1000 个 Token 约等于 750 个英文单词或 400～500 个汉字。
- 每个 GPT 模型都有预设的最大 Tokens 数量，例如 GPT-3 每次调用最多支持 4096 个 Token，而 GPT-4 则支持 3 万多个。

OpenAI 官网提供了一个 [Tokenizer 工具](https://platform.openai.com/tokenizer)，帮助你计算文本与 Token 长度的对应关系。

![Tokenizer 工具](https://bbtdd.com/img/3928171661.webp)

例如，“我是刘志军” 5 个字符占用了 9 个 Token。

---

## API 计费规则

GPT-3.5 的价格非常便宜，1000 个 Token 的价格为 0.002 美元，约合人民币 2 分钱。而 GPT-4 的价格则比 GPT-3 贵了近 6 倍。

![API 计费](https://bbtdd.com/img/763589962482061.webp)

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

---

以上就是关于 ChatGPT API 额度、Token 和价格的全面解析。无论是开发者还是普通用户，了解这些细节都能更好地利用 ChatGPT 的强大功能。