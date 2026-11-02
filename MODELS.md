# NexoToken 会员型号与销售价格快照

核对日期：2026-11-02。此表只覆盖会员分组，单位为**平台虚拟美元 / 百万 Token**，不是人民币或可提现美元。家族、版本和别名按平台目录展示，20 个条目不代表 20 种独立能力。目录不构成实际调用测试。

| 模型 ID | 展示名称 | 输入 | 输出 | 缓存读取 | 缓存写入 | 公开长上下文阈值 |
|---|---|---:|---:|---:|---:|---:|
| claude-fable-5 | Claude Fable 5 | 10.0 | 50.0 | 1.0 | 12.5 | 未提供 |
| claude-fable-5-1 | Claude Fable 5.1 | 10.0 | 50.0 | 0.25 | 12.5 | 未提供 |
| claude-haiku-4-5-20251001 | Claude Haiku 4.5 | 1.0 | 5.0 | 0.1 | 1.25 | 未提供 |
| claude-opus-4-6 | Claude Opus 4.6 | 5.0 | 25.0 | 0.5 | 6.25 | 未提供 |
| claude-opus-4-7 | Claude Opus 4.7 | 5.0 | 25.0 | 0.5 | 6.25 | 未提供 |
| claude-opus-4-8 | Claude Opus 4.8 | 5.0 | 25.0 | 0.5 | 6.25 | 未提供 |
| claude-opus-5 | Claude Opus 5 | 5.0 | 25.0 | 0.5 | 6.25 | 未提供 |
| claude-opus-5-5 | Claude Opus 5.5 | 4.0 | 20.0 | 0.2 | 5.0 | 未提供 |
| claude-sonnet-4-6 | Claude Sonnet 4.6 | 3.0 | 15.0 | 0.3 | 3.75 | 未提供 |
| claude-sonnet-5 | Claude Sonnet 5 | 2.0 | 10.0 | 0.2 | 2.5 | 未提供 |
| claude-sonnet-5-5 | Claude Sonnet 5.5 | 2.0 | 10.0 | 0.1 | 2.5 | 未提供 |
| gpt-5.6-sol | GPT-5.6 Sol | 4.0 | 20.0 | 0.4 | 5.0 | 272000 |
| gpt-5.6-terra | GPT-5.6 Terra | 2.0 | 12.0 | 0.2 | 2.5 | 272000 |
| gpt-6-astra | gpt-6-astra | 10.0 | 50.0 | 1.0 | 12.5 | 272000 |
| gpt-6-sol | GPT-6 Sol | 2.0 | 10.0 | 0.2 | 2.5 | 272000 |
| gpt-6.1-sol | GPT-6.1 Sol | 2.0 | 10.0 | 0.1 | 2.5 | 272000 |
| gpt-6.1-terra | GPT-6.1 Terra | 1.0 | 5.0 | 0.05 | 1.25 | 272000 |
| grok-4.5 | Grok 4.5 | 2.0 | 6.0 | 0.3 | 未提供 | 200000 |
| grok-4.6 | Grok 4.6 | 2.0 | 6.0 | 0.5 | 未提供 | 200000 |
| grok-4.7 | Grok 4.7 | 2.0 | 6.0 | 0.5 | 未提供 | 200000 |

阈值为输入 Token 的公开分档参考，不能当作最大上下文能力。超过阈值时应查询对应分档价格；表中基础价格不适用于任意长度。未提供缓存价格不等于免费。缓存写入时效、多档价格及额外工具费需要另外确认。

销售积分字段按 100 积分 / 平台虚拟美元归一化；不包含内部成本。机器可读数据见 [pricing-snapshot.json](pricing-snapshot.json)。

来源：[NexoToken 公开模型配置](https://www.nexotoken.net/api/models/config?channel=membership)。购买限制和当前套餐见 [README](README.md)。
