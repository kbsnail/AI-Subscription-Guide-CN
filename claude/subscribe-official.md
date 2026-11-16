# Claude Pro / Max / Ultra 官方订阅：价格、地区条件与操作步骤

> 适用：想了解 Claude 官方套餐价格、自己是否符合官方订阅条件、以及在官网如何完成订阅的读者。
> 最后核对日期：2026-11-16。价格与套餐名称以 [Anthropic 官网定价页](https://claude.com/pricing) 实时显示为准。

## 先说结论

- Claude Pro 官方价格：**20 美元/月，或 200 美元/年**（年付折合约 17 美元/月）。
- 更高档位原为 Max 5x（100 美元/月）与 Max 20x（200 美元/月）。**Anthropic 于 2026-10-30（美国时间，[@claudeai 官方公告](https://x.com/claudeai/status/2116220869479428500)，北京时间 10-31）将 Max 5x 更名为 Max、Max 20x 更名为 Ultra**，价格不变，原 Max 20x 订阅自动转入 Ultra（[官方帮助中心](https://support.claude.com/en/articles/17728952-what-is-the-ultra-plan)）。本文按新名称书写，并保留旧名称对照。
- **中国大陆、香港、澳门不在 Anthropic 官方支持地区名单内。** 看到官网价格不等于能按官方路径完成订阅。
- **Pro 是聊天产品订阅，不包含 API 调用额度**；Claude Console 的 API 计费是另一套体系。
- Pro 有更高使用额度，但**不是无限使用**，实际用量受会话长度、附件大小、模型选择等因素影响。

## 官方套餐一览

| 套餐 | 官方公开价格 | 旧名称（更名前） | 更适合谁 |
| --- | --- | --- | --- |
| Claude Pro | 20 美元/月；200 美元/年 | — | 大多数个人用户 |
| Claude Max | 100 美元/月（仅月付） | Max 5x | 高频使用者 |
| Claude Ultra | 200 美元/月（仅月付） | Max 20x | 极重度使用者 |

补充说明（2026-11-16 按 [官方定价页](https://claude.com/pricing)与帮助中心核对）：

- **用量倍数（官方口径）：** Max 为 Pro 的 **5 倍**（每 5 小时与每周均适用）；Ultra 为 Pro 的 **每周 10 倍**。两档都有跨模型的每周限额，Fable 模型另有单独的每周限额。
- **Ultra 的「无 5 小时限制」有条件：** 官方说明仅对**已验证账户（verified accounts）**免除 5 小时限制；未验证账户有临时限制，验证通过后自动解除（验证由 Anthropic 按账户与付款历史自动完成，[官方说明](https://support.claude.com/en/articles/17728952-what-is-the-ultra-plan)）。
- **月度 API 额度（API credits，用于 Claude Platform，不是聊天或 Claude Code 用量）：** Max 每月 $100、Ultra 每月 $200；**Pro 档不含 API 额度**。按[官方帮助中心](https://support.claude.com/en/articles/17154008-monthly-api-credits-for-max-ultra-and-team-plans)（2026-11-16 核对）：订阅须处于有效状态，新订阅者需在档满 7 天后才能领取；在 claude.ai 网页版 Settings > Billing 的 API credits 入口绑定一个 Console 组织领取（iOS / Android 订阅也在网页端领取），额度每月发放到该组织，绑定后不能自行更换组织；领取无需在 Console 绑卡。额度可用于 Claude API、Console Playground、Managed Agents 与 Agent SDK，**不适用于交互式 Claude Code，也不适用于 Claude / Claude Code / Cowork 的额外用量**；每个计费周期刷新（年付订阅也按月发放），当期未用完即过期、不结转，且不改变套餐本身的使用限额。
- Claude Code 的使用权限与套餐相关：Pro / Max / Ultra 均包含 Claude Code 访问能力（与聊天共用同一用量池），但能否长期稳定使用还取决于账号、网络环境与风控情况，不能只看套餐名。
- 以上档位信息原教程记录于 2026-04-15（当时名称为 Max 5x / Max 20x），套餐更名与额度细节由本整合于 2026-11-15 核对、2026-11-16 按官方公告与帮助中心复核更新；具体权益以官网当前说明为准。

## 两个最容易理解错的地方

**误会一：看得到价格，就等于买得到。**
Anthropic 公布的支持地区名单里没有中国大陆、港澳。地区不在名单内时，注册、访问、支付各环节都可能遇到门槛；换一张 Visa 卡、改账单地址或找人代付，都不会把所在地区变成官方支持地区。

**误会二：买了 Pro，就等于 API 也能一起用。**
帮助中心写得很清楚：聊天产品订阅和开发者 API 计费是分开的。买 Pro 提升的是网页版、桌面端和移动端的使用权限；要把 Claude 接进自己的产品调 API，需要另外在 Console 开通计费。这一点与 ChatGPT 会员和 OpenAI API 的关系相同，参见 [ChatGPT 套餐选择](../chatgpt/plus-vs-pro.md)。

## 官方订阅步骤（符合地区与付款条件时）

前提：本人位于 Anthropic 支持地区，持有支持地区发卡机构的银行卡，网络环境稳定干净。

1. **注册 / 登录账号**：打开 [claude.ai](https://claude.ai/)，用邮箱注册或登录。部分地区注册时可能要求手机号验证。
2. **进入升级入口**：登录后在页面找到 Upgrade / 升级套餐入口，选择 Pro（或 Max / Ultra）。
3. **核对金额并付款**：确认套餐、周期、含税总额与下次扣款日期，填写海外银行卡号、有效期、CVC 和银行记录中的真实账单地址，完成银行验证。逐项填写与拒付处理见 [海外银行卡逐项填写](../guides/international-card.md)。
4. **核对订阅**：付款后回到账号设置查看订阅状态与收据；网页版、桌面端、移动端登录同一账号即可使用。

国内银行卡（包括国内银行发行的双币 Visa / Mastercard）大多无法完成付款：清算通道走国内体系，平台识别后直接拒掉。这不是换一张卡再试就能解决的问题，反复失败还会给账号累加风控分。

## 不符合官方条件怎么办

- 先认清地区限制这一事实，再决定路线。各路线的对比与风险见 [Claude 订阅方式总览](./subscription-methods.md)。
- iPhone / iPad 用户可以了解 [iOS 礼品卡内购路线](./subscribe-ios.md)。
- 考虑第三方服务时，先读 [第三方订阅风险与挑选标准](../chatgpt/third-party-subscription.md)（判断标准对 Claude 同样适用）。
- 任何路线都要求稳定、干净、能访问官网的网络环境，见 [网络环境要求](../guides/network-environment.md)。

## FAQ

**Q：中国大陆能直接买 Claude Pro 吗？**
A：从 Anthropic 官方公布的支持地区列表看，中国大陆不在 Claude.ai 支持名单内，港澳也不在。很多中文用户会在注册、访问或支付环节遇到门槛。

**Q：Claude Pro 能用国内信用卡吗？**
A：官方没有承诺支持所有地区的本地支付方式。实际能否支付与地区、卡种、账单地址、风控判断都有关系，没有「一定行」或「一定不行」的绝对答案；但大陆发行的卡被拒是普遍现象。

**Q：Max / Ultra 值得买吗？**
A：看使用强度。普通写作、日常问答、轻度编码，Pro 通常够用；每天高强度使用（尤其是 Claude Code 写代码）再考虑 Max / Ultra。

**Q：买了 Pro 就能稳定用 Claude Code 吗？**
A：套餐包含 Claude Code 访问能力，但长期稳定性还取决于账号本身、网络环境、地区和实际风控情况，不能只看套餐名。

**Q：官方订阅能退款吗？**
A：按官方定价页 FAQ，订阅费用一般不可退，除非消费者条款或适用法律另有规定（例如欧洲经济区 / 英国的 14 天撤回权）；通过 App Store 内购的订阅按 Apple 的退款政策处理，Google Play 内购联系对应支持渠道。取消订阅需在续费前至少 24 小时操作，取消不等于退款。

## 相关教程

- [Claude 订阅方式总览](./subscription-methods.md)
- [Claude iOS 礼品卡订阅](./subscribe-ios.md)
- [Claude 充值与使用常见问题](./payment-issues.md)
- [海外银行卡逐项填写](../guides/international-card.md)
- [网络环境要求](../guides/network-environment.md)

---

## 来源与修改说明

- 来源仓库：[ClaudePro](https://github.com/pwna11/ClaudePro)（pwna11，无许可证文件，已获作者本人许可，见 [SOURCES](../SOURCES.md)）。
- 原始文档：README《2026 最新 Claude 充值教程》官方规则部分（记录于 2026-04-15）。
- 修改情况：保留官方价格、地区规则、Pro 不含 API、非无限额度等事实与 FAQ；**删除 claudepro.org 充值平台推广与全部导流链接**；套餐名称按官方更名更新（Max 5x→Max、Max 20x→Ultra），官网订阅步骤为按官方流程整理的通用说明，非原作者实测。2026-11-16 复核：更名日期更正为官方公告日 2026-10-30（美国时间，北京时间 10-31）并附官方出处；补充 Max 5 倍 / Ultra 每周 10 倍的官方用量口径、Ultra 无 5 小时限制仅限已验证账户的条件、Max $100 / Ultra $200 月度 API 额度（含领取条件、适用范围与不结转规则，按官方帮助中心 17154008 核对）、Max/Ultra 仅月付，以及官方退款 FAQ。
- 图片来源：无（原仓库配图为推广图，未采用）。
- 原教程记录日期：2026-04-15；本整合核对日期：2026-11-15。原教程记录于 2026-04-15，当前可用性尚未重新验证；套餐名称与权益已按 2026-11 官方信息更新。