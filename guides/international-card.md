# 有海外银行卡，怎么在 ChatGPT 官网直接订阅 Plus？

> 适用：本人和发卡银行都位于 OpenAI 支持地区、持有真实可用海外银行卡的用户。
> 最后核对日期 2026-11-15。这是最省钱、最正规的路线：官方原价，订阅绑在自己账号上。

## 先说结论

在 [chatgpt.com](https://chatgpt.com) 登录要升级的账号 → Settings → Upgrade plan → Get Plus → 填卡号、有效期、CVC 和**银行登记的真实账单地址** → 完成 3D Secure 验证 → 回 Settings → Billing 核对 Plus 与收据。$20/月 + 当地税，没有任何溢价。

**国内银行发行的卡不在官方支持范围内**，包括双币 Visa、Mastercard 卡——看的是发卡银行所在地，不是卡面标志。中国大陆、香港、澳门都不在 [OpenAI 支持地区名单](https://help.openai.com/en/articles/7947663-chatgpt-supported-countries) 里（2026-10-27 核对）。只换账单地址不能改变真实发卡地区，别反复试同一张卡。

## 付款前准备三样东西

1. **要升级的 ChatGPT 账号。** 已有 Plus 时先确定原订阅在哪个平台，避免重复购买。
2. **真实可用的海外信用卡或借记卡。** 向发卡银行确认支持线上、国际和定期扣费，且可完成 3D Secure / 银行 App 验证。
3. **这张卡在银行登记的真实账单姓名、地址和邮编。** 付款页不要填与银行记录不符的地址。

## 从官网到支付成功，逐步点

1. **登录并核对套餐。** 在浏览器打开 chatgpt.com，用要开通的账号登录。点头像或菜单 → Settings / 设置，确认当前套餐及账单状态，避免再次买到已有的 Plus。
2. **选择 Plus。** 点「Upgrade plan / 升级套餐」，在个人套餐里选「Get Plus」。不要选团队版、Pro 或 API 余额。
3. **核对价格与续费日期。** 在结算页先读清月费、币种、税费与续费日期。网页结算按页面实际金额收费；当地税可能使总额高于基础套餐价。截至 2026-09-10，OpenAI 公开页面显示 Plus 为 20 美元/月（来源 D 的核对记录），税费和最终金额以结算页为准。
4. **填写银行卡资料。** 填卡号、到期月年和 CVC；账单姓名、地址、城市、州省和邮编按发卡银行记录填写。逐项确认后提交一次，不要连续点付款按钮。
5. **完成银行验证。** 银行若弹出 3D Secure 验证，按银行 App 或短信完成确认，**保持结算页打开**。关闭弹窗或验证码过期会导致付款失败。
6. **检查订阅与收据。** 完成后回原 ChatGPT 账号，打开 Settings → Billing / 账单核对 Plus、收据及下次扣款日期。保存收据；下月不用时从同一账单页取消，别只锁卡。

另一来源（A01）的补充经验：挂一个稳定干净的美区节点再操作；别用国内双币卡硬试超过一两次，失败多了会给账号累加风控标签（原作者经验判断）。

## 变体：海外亲友代付

如果家人朋友在国外，可以让他们用自己的卡登录你的账号帮你订阅一次，之后每月自动扣他们的卡，你再按月把钱转给他们。零溢价、最省钱。缺点是对方换卡/销卡时你的订阅会断，得记得结清。适合有稳定海外关系的人。

**别把「找陌生代付中介」当成这一类**——那本质上是第三方代充（见 [第三方订阅风险](../chatgpt/third-party-subscription.md)），还没有售后。

## 卡被拒后怎么定位

| 情况 | 处理 |
| --- | --- |
| 中国大陆发行的国际卡被拒 | OpenAI 要求发卡银行位于支持地区；只换账单地址不能改变发卡地。不要反复试同一张卡，改走 [礼品卡路线](./apple-gift-card-pockyt.md) 或其他方案 |
| 支持地区发行的卡被拒 | 核对卡号、有效期、CVC、银行记录中的账单地址、余额与银行交易限制；联系发卡行说明是境外在线周期订阅 |
| 3D Secure 未完成 | 允许支付验证弹窗和跳转，在银行 App 完成批准；仍不弹出时用无痕窗口或换浏览器，并让银行核查验证是否启用 |
| 有扣款却没 Plus | 先看收据与同一账号的 Billing，确认是否只是银行预授权；联系 OpenAI 支持并附交易时间、错误文字，不发送完整卡号 |

更完整的按提示分类排查见 [付款失败怎么办](../chatgpt/payment-failed.md)。

## 怎么取消

登录购买时的 ChatGPT 账号，头像 → Settings → Billing → Cancel plan → Cancel。OpenAI 说明最好在下次扣费日前至少 24 小时取消；取消后通常可用到已付款周期结束。详见 [续费、取消与退款](../chatgpt/renewal-and-refund.md)。

## 没有海外卡怎么办

没有受支持地区银行卡的人，可比较 [Apple 礼品卡路线](./apple-gift-card-pockyt.md)、[虚拟卡条件与费用](./virtual-card.md) 和 [第三方代充服务](../chatgpt/third-party-subscription.md)，但这些路线都不会改变 OpenAI 官方地区限制。

## 相关教程

- [ChatGPT 官网自助订阅（含官方 App）](../chatgpt/subscribe-official.md)
- [付款失败排查](../chatgpt/payment-failed.md)
- [虚拟卡路线](./virtual-card.md)
- [网络环境要求](./network-environment.md)

---

## 来源与修改说明

- 来源仓库：[GPTplusSub](https://github.com/laoma528/GPTplusSub)（laoma528，无许可证，经项目负责人确认授权，`foreign-card.html`）；[chatgpt-plus-subscription-guide](https://github.com/daydayup-xq/chatgpt-plus-subscription-guide)（daydayup-xq，CC BY 4.0，方法一）；[chatgpt-plus-china-guide](https://github.com/Avarce/chatgpt-plus-china-guide)（Avarce，无许可证，经项目负责人确认授权，路线 A 与亲友代付变体）。
- 修改情况：合并三个来源的官网直付步骤，保留各自补充点；删除原站 ProdClub 导流链接；「我们」改为「原作者」；内部链接改为本站相对链接。
- 图片来源：本篇无图片。
- 原教程记录日期：2026-11-14（L）、2026-09-10（D）、2026-11-12（A）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。
