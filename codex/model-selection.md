# Codex 模型怎么选？三个推荐档位与推理强度

> 适用：已开通 Codex，面对多个模型档位和推理强度不知道如何选择的读者。
> 最后核对日期：2026-11-15。模型名单与评分随版本更新变化，以 Codex 当前可选档位为准。

## 先说结论

原作者主要用 Codex 写代码、做调研和自动化任务，按任务**直接选择以下三个档位，不用逐级尝试**：

| 模型档位 | 雷达 IQ | 推荐用途 |
| --- | --- | --- |
| GPT-5.6 Luna Max | 100 | 简单需求，优先节省额度 |
| GPT-6.1 Sol High | 暂无分数 | 需求明确、有测试和验收机制的工程开发 |
| GPT-6 Astra Medium | 117 | 最强档位，用于方案、机制、架构和 Skill 设计 |

IQ 参考 [Codex Radar](https://codexradar.com/) 的综合智能评分，记录于 2026-10-01，随众测更新；当前分数以该站实时数据为准。

**不推荐 GPT-6 Luna**：Max 档的雷达 IQ 只有 82，原作者使用下来也觉得效果较差。要省额度，仍然推荐 GPT-5.6 Luna Max。

## 为什么 Sol High 是工程开发主力

- 从原作者的[鹈鹕测试](./troubleshooting.md)看，GPT-6.1 Sol High 的生成效果比较接近 GPT-6 Astra Medium。
- 雷达暂未给出 GPT-6.1 Sol High 的分数，原作者估计其 IQ 高于 GPT-6 Sol High（103）。这是原作者基于实测的**估计**，不是官方评分。
- 选择原则：**需求明确、能通过测试验收的任务，优先用 Sol High；更依赖判断力、需要权衡方案的工作，直接用 Astra Medium。**

## 模型选择与额度消耗的关系

模型和推理强度会影响额度消耗，也要结合完成任务的速度来选择：

- 简单任务用高档位是浪费额度；复杂任务用低档位可能反复返工，反而更费。
- 按上面的三档对号入座，比「一律拉满」或「一律省钱」都更划算。
- 额度成本与中转性价比的量化分析见 [Codex 周额度与中转性价比](./usage-and-limits.md)。

## FAQ

**Q：这些模型名称是官方当前的吗？**
A：档位名单记录于 2026-11-09（原教程最后更新）。OpenAI 会随版本调整模型名单与命名，操作时以 Codex 内实际可选档位为准；选择思路（省额度档 / 工程主力档 / 最强档）仍然适用。

**Q：IQ 分数是谁测的？**
A：来自第三方众测站 Codex Radar 的综合智能评分，不是 OpenAI 官方指标，仅供参考。

**Q：怎么知道我的模型有没有被「降智」替换？**
A：用鹈鹕测试快速自测，见 [Codex 降智自测与恢复](./troubleshooting.md)。

## 相关教程

- [Codex 开通、二次验证与登录](./subscription-and-access.md)
- [Codex 周额度与中转性价比](./usage-and-limits.md)
- [Codex 降智自测与恢复](./troubleshooting.md)

---

## 来源与修改说明

- 来源仓库：[chatgpt-plus-codex-cn-guide](https://github.com/cabbagecabbage/chatgpt-plus-codex-cn-guide)（cabbagecabbage，CC BY-NC-SA 4.0，商业使用已获授权）。
- 原始文档：`docs/model-selection-and-reasoning.md`《Codex 模型与推理强度选择：三个推荐档位》（2026-11-09 更新）及 README 第十三章。
- 修改情况：保留三档推荐表、IQ 参考、Sol High 判断依据与不推荐 GPT-6 Luna 的结论；「楼主」改为「原作者」，其 IQ 估计明确标注为个人估计；补充模型名单时效提示与站内链接。
- 图片来源：无（本文无配图；鹈鹕测试对比 GIF 见降智一文）。
- 原教程记录日期：2026-10-01（IQ 评分）至 2026-11-09（最后更新）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。