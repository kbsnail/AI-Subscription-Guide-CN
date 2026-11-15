# Apple 礼品卡怎么兑换？兑换失败、余额不足与恢复购买排查

> 适用：已经买到礼品卡兑换码，准备充值到 Apple 账户并订阅 ChatGPT / Claude 的用户。
> 最后核对日期 2026-11-15。Apple 的兑换与扣费规则可能变化，以页面实际提示为准。

## 先分清三种礼品卡

给 ChatGPT 充值前，先分清礼品卡的发行方和兑换入口（来源 GPTplusSub，2026-11-14 更新）：

| 名称 | 由谁发行 | 在哪里用 | 大陆读者先看什么 |
| --- | --- | --- | --- |
| Apple Gift Card / App Store 卡 | Apple | 兑换到对应国家或地区的 Apple 账户余额；符合条件时在官方 ChatGPT iOS App 的 Apple 内购中付款 | Apple 账户地区必须与卡的地区匹配；Apple 可能要求当地有效付款方式。它不能在 ChatGPT 网页结算时直接当银行卡 |
| OpenAI ChatGPT Gift Card | OpenAI 授权渠道 | 符合资格时在 chatgpt.com/redeem 兑换到 OpenAI 钱包，再用于网页端合格消费 | OpenAI 当前仅允许在美国购买和兑换，要求美国账户与美元账单；大陆账号不能把它当通用充值码 |
| 第三方商家卡密 | 销售该卡密的商家 | 按该商家自己的兑换页和条款使用 | 先找清楚发行方、商家兑换地址和售后；不要把它称作 OpenAI 官方礼品卡 |

**兑换余额不等于已经开通 Plus。** Apple 余额和第三方卡密也不能直接当作 ChatGPT 网页的付款卡。

OpenAI 礼品卡的官方说明见 [Buying and redeeming OpenAI gift cards](https://help.openai.com/en/articles/20001491-buying-and-redeeming-openai-gift-cards)：即便符合条件，兑换礼品卡只会给钱包加余额，不会自动开通 Plus；还要在同一 ChatGPT 账号的网页结算中选择套餐。它不能支付 Apple 或 Google 的内购。

## 兑换前核对三件事

1. **卡与账户地区一致。** 美区礼品卡只能给美区 Apple 账户使用，日区礼品卡只能给日区账户使用。Apple 明确说明跨地区购买的卡不能在另一地区兑换（[Apple 礼品卡地区限制](https://support.apple.com/en-gb/108285)）。
2. **核对当前 App Store 登录的 Apple 账户。** 在 iPhone「设置 → 你的姓名 → 媒体与购买项目」查看将用于 App Store 的账户；再打开 App Store → 头像，确认是同一个。iCloud 账户和媒体购买账户可以不同，不要为了买卡直接退出承载照片、备忘录的 iCloud 账户。
3. **检查已有订阅。** 检查「设置 → 你的姓名 → 订阅」是否已有 ChatGPT 订阅；同时在 ChatGPT 设置查看当前账号套餐。已有付费订阅先弄清原结算方，避免重复扣费。

## 兑换步骤

1. 进入 iPhone 或 iPad 的 **App Store**，点右上角头像。
2. 选择「**兑换充值卡或代码**」（英文界面 Redeem Gift Card or Code）。
3. 选择相机扫描或「**手动输入代码**」，输入购买得到的兑换码，点「兑换 / Redeem」。
4. 确认兑换后，回到头像页检查 **Apple 账户余额**是否增加；余额会显示在名字下面。

实操截图可参考 [SEAGM 教程的第 ⑱–⑲ 步](./apple-gift-card-seagm.md#支付宝付款拿兑换码兑换⑬⑲)。兑换码要妥善保存，不要公开。

## 兑换后订阅

在 iOS 版官方 ChatGPT App 登录要升级的 OpenAI 账号 → Upgrade → 使用 Apple ID Balance 完成付款，付款前确认总额是 $19.99（账单州 Oregon）。完整流程见 [ChatGPT iOS 订阅教程](../chatgpt/subscribe-ios.md)。

**新注册的美区 Apple ID** 建议先买一两个便宜 App 再订 Plus，降低触发 Apple 购买审核的概率，见 [注册教程第三步](./apple-id-registration.md#第三步建议新账号先买一两个便宜-app)。

## 失败时按屏幕提示处理

| 看到什么 | 具体下一步 |
| --- | --- |
| 代码不能兑换 / 地区不符 | 对照礼品卡标注的发行地区和 App Store 当前 Apple 账户地区；不一致就联系原卖家处理，不能拿美国卡去中国区兑换 |
| This code has already been redeemed | 这张卡已经被兑换过。来源不明的低价卡密容易遇到这种情况；从有公司主体、能查订单的渠道买（如 [Pockyt](./apple-gift-card-pockyt.md)、[SEAGM](./apple-gift-card-seagm.md)），风险小得多。买到这种卡，先联系卖家 |
| 余额已到账，Apple 仍要求付款方式 | 查看购买弹窗的含税总额与余额；若仍不足先补足（多半是账单地址不在免税州被加了税，见 [iOS 订阅教程排查段](../chatgpt/subscribe-ios.md#付款时提示必须提供付款信息才能继续购买)）。金额足够仍要求卡时，按 Apple 对该账户的支付要求操作或联系 Apple 支持，不要填写虚假资料 |
| 扣费成功，ChatGPT 还是 Free | 核对 App 登录的是付款时的 ChatGPT 账号；在 ChatGPT 设置 → Account / 账户 → **Restore purchases / 恢复购买**（[OpenAI 官方排查步骤](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)）。仍失败时用 Apple 收据向 OpenAI 支持说明，不要立即再买一份 |
| 下个月不想续 | iPhone「设置 → 你的姓名 → 订阅 → ChatGPT → 取消订阅」。只删除 App 不会取消 Apple 订阅 |

**兑换失败时先不要重复买第二张卡**，按上表排查。

## 常见问题

**Q：礼品卡是直接充值到 ChatGPT / Claude 账号吗？**
A：不是。先充值到 Apple 账户余额，再在 ChatGPT / Claude App 内完成订阅。（来源 GetClaudeProByAppleIO FAQ）

**Q：chatgpt.com 网页端的 Apple Pay 能用礼品卡余额吗？**
A：不能。Apple 列出的余额用途是 App Store 里的 App、App 内购买和订阅，以及 apple.com 上的产品等（[Apple 礼品卡和余额能买什么](https://support.apple.com/zh-cn/118245)），不包括其他网站。网页结账里的 Apple Pay 用的是钱包里的银行卡，礼品卡余额只能在 iOS 版 ChatGPT App 里付。

**Q：充值成功的账号可以在电脑网页端使用吗？**
A：可以。订阅绑定在 ChatGPT 账号上，和信用卡充值的账号一样可以在网页端使用，前提是登录同一个 ChatGPT 账号。

**Q：余额不够付这一笔怎么办？**
A：余额不足时 Apple 会从主要付款方式扣费（[Apple 扣费规则](https://support.apple.com/zh-cn/118244)）；付款方式是 None 时就会要求你提供付款信息。优先把账单地址改成免税州，或再兑换一张礼品卡补足。

## 相关教程

- [支付宝买美区礼品卡（Pockyt）](./apple-gift-card-pockyt.md)
- [SEAGM 买美区礼品卡](./apple-gift-card-seagm.md)
- [Apple 官网买礼品卡](./apple-gift-card-official.md)
- [ChatGPT iOS 订阅完整流程](../chatgpt/subscribe-ios.md)
- [续费、取消与退款](../chatgpt/renewal-and-refund.md)

---

## 来源与修改说明

- 来源仓库：[GPTplusSub](https://github.com/laoma528/GPTplusSub)（laoma528，无许可证，经项目负责人确认授权，`gift-cards.html`、`apple-gift-card.html`）；[chatgpt-plus-china-guide](https://github.com/Avarce/chatgpt-plus-china-guide)（Avarce，无许可证，经项目负责人确认授权，兑换三步与 already-redeemed 排查）；[chatgpt-plus-subscription-guide](https://github.com/daydayup-xq/chatgpt-plus-subscription-guide)（daydayup-xq，CC BY 4.0，地区配对原则）；[GetClaudeProByAppleIO](https://github.com/sunreview/GetClaudeProByAppleIO)（sunreview，无许可证，经项目负责人确认授权，FAQ）。
- 修改情况：合并兑换步骤与失败排查表；删除原站 ProdClub 代充导流内容与链接；内部链接改为本站相对链接；保留官方帮助文档引用。
- 图片来源：本篇不新增图片，兑换截图复用 SEAGM 教程中的已遮挡图片。
- 原教程记录日期：2026-11-14（L）、2026-11-12（A）、2026-09-10（D）、2026-10-06（S）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。
