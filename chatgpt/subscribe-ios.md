# iPhone 怎么订阅 ChatGPT Plus？美区 Apple ID + 礼品卡完整流程

> 适用：有 iPhone 或 iPad，没有海外信用卡，准备用美区 Apple ID + 礼品卡余额订阅的用户。Claude 等有 iOS 端的产品同理。
> 最后核对日期 2026-11-15。核心步骤来自多个来源作者的实测；价格与界面以页面实际显示为准。

## 先说结论

准备美区 Apple ID → 买 $20 美区礼品卡 → App Store 兑换 → 在官方 ChatGPT App 内用余额订阅 Plus（$19.99，账单州 Oregon 无税）。订阅绑定在你登录的 OpenAI 账号上，开通后网页端、Mac、安卓都能用。

**为什么这条路线稳定：** 付款由 Apple App Store 处理，不走 OpenAI 网页端的 Stripe 支付流程（来源 A）。

## 开始前：三个必须知道的事

### 1. 一个 Apple ID 只能给一个 ChatGPT 账号订阅

首次通过 Apple 内购订阅后，Apple ID 就与本次订阅的 ChatGPT 账号永久绑定，按原作者记录时的政策无法解绑或换绑。第一次付款就要选好准备长期使用的 ChatGPT 账号。完整例子和踩坑记录见 [账号安全与付款前检查](../guides/account-security.md#一个-apple-id-只能给一个-chatgpt-账号订阅永久绑定)。

### 2. 确认你的 Apple 账号是免税区

付款前，确认美区 Apple ID 的账单地址在免税州（推荐 Oregon）。本文的订阅金额均按免税区计算。原因见 [Apple ID 改区教程](../guides/apple-id-region-change.md#为什么账单州要选-oregon免税州)。

### 3. Apple ID 和 ChatGPT 账号一定要自己注册

千万不要购买批量注册的账号，不然付费后封号的风险非常高（来源 W 反复强调）。

## 完整流程

### 第一步：准备美区 Apple ID

- 还没有：[注册美区 Apple ID](../guides/apple-id-registration.md)（推荐，主力 iCloud 不动），或把现有账号[改成美区](../guides/apple-id-region-change.md)。付款方式选 None，账单州选 Oregon。
- 已经有美区 Apple ID：直接看第二步。
- 只切换「媒体与购买项目」，不必退出整台手机的 iCloud 和 iMessage。

### 第二步：买 $20 美区礼品卡

三个渠道任选（都是原作者实测过的路线）：

| 渠道 | 付款方式 | 参考成本（历史记录） | 教程 |
| --- | --- | --- | --- |
| Pockyt Shop（支付宝内） | 支付宝 | $20 卡 ¥134.44（2026-10-13 复测） | [6 步实测](../guides/apple-gift-card-pockyt.md) |
| SEAGM（网页） | 支付宝 | $20 卡 ¥138.13（2026-11-06 实测） | [19 步实测](../guides/apple-gift-card-seagm.md) |
| Apple 官网 | 国内银联卡 | 面额 $20 + 可能的汇率差 | [8 步图文](../guides/apple-gift-card-official.md) |

第一次购买建议只买够一个月使用的金额，不要一开始就在账户里存很多余额。

### 第三步：兑换礼品卡

App Store → 右上角头像 → 兑换充值卡或代码 → 手动输入代码 → 确认余额到账。详见 [礼品卡兑换教程](../guides/apple-gift-card-redemption.md)。

### 第四步：在 ChatGPT App 内订阅

综合来源 C（2026-11-09）与来源 D（2026-09-10）的步骤：

1. 使用准备付款的美区 Apple ID 登录 App Store，下载 OpenAI 官方 ChatGPT App（确认开发者是 **OpenAI** 或 **OpenAI OpCo, LLC**）。
2. 在 ChatGPT App 登录准备长期使用的目标账号，核对邮箱和登录方式。
3. 确认 App Store「媒体与购买项目」显示的是准备扣款的 Apple ID。
4. 在 ChatGPT App 打开套餐升级入口（对话页顶部「Get Plus / 升级」，或侧边菜单 → 你的姓名 → 设置 → Upgrade），选择 ChatGPT Plus。按钮文字可能随版本改变。
5. 确认弹出的是 **Apple 的 App Store 购买确认框**。若跳到浏览器的网页结算，那是另一条付款路径，Apple 余额不会自动用于网页卡支付；返回 App 检查实际可用的内购选项。
6. 核对套餐、金额（应为 $19.99）、续费周期和付款 Apple 账户，使用面容 ID、触控 ID 或设备密码确认。
7. 回到 ChatGPT，确认 Plus 已经到账；再到 iPhone「设置 → 你的姓名 → 订阅」确认 ChatGPT 由 Apple 管理。

**新注册的美区 Apple ID：** 先买一两个便宜 App 再订 Plus，降低触发购买审核的概率，见 [注册教程第三步](../guides/apple-id-registration.md#第三步建议新账号先买一两个便宜-app)。

## 想在 iPhone 上订 Pro？先 Plus 再升级

来源 C 的实测方法（2026-11-09 记录）：

1. 按上面的步骤，在 ChatGPT App 中通过 Apple 内购订阅 **$20/月的 Plus**。
2. 打开 **App Store → 右上角头像 → 订阅 → ChatGPT → 查看所有方案**，选择 **$100/月的 Pro** 或 **$200/月的 Pro**。也可以从 **iPhone 设置 → 你的姓名 → 订阅 → ChatGPT → 查看所有方案**进入。

按 [OpenAI 的说明](https://help.openai.com/en/articles/7905739-chatgpt-ios-app-upgrading-to-a-paid-subscription)，Free 直接升 Pro 要去网页端，所以在 iPhone 上只能先订 Plus 再升级 Pro（来源 A，2026-10-22 核对美区 App Store 的 ChatGPT 页面列有 Pro 100 $100、Pro 200 $200）。

**余额要够付 Pro 的全额，不能只准备差价。** 以 $200 方案为例：先扣 $20 开 Plus，切换 Pro 时，Apple 账户里还要有足够支付 $200 的余额，然后再扣 $200。也就是说，若从零开始、全部用余额付款，退款前需要先准备 **$220**；$100 方案同理，需要先准备 **$120**。

原作者开通 Plus 后立刻切换到 20 倍 Pro，升级后 1～2 天内，完整的 $20 退回了 Apple 账户余额。退款在升级后到账，不会提前抵扣 Pro 的付款。

> 注意：来源 C 记录当时 $200 的 Pro 曾暂停新购和升级（[OpenAI 套餐说明](https://help.openai.com/en/articles/9793128)）；来源 A 记录 9 月 29 日 DevDay 后 Pro 200 已重新开放。套餐开放状态以官方页面为准。Pro 各档区别见 [Plus 和 Pro 怎么选](./plus-vs-pro.md)。

**一次花 $100 以上，更容易被 Apple 拦下审核**，弹出「购买未完成，提交申请至 Apple 支持以供审核」，刚注册或刚改到美区的 Apple ID 尤其容易遇到（来源 A）。新注册的账号先买一两个便宜 App，再正常订几个月 Plus，有了购买记录再充大额余额。

## 付款时提示「必须提供付款信息才能继续购买」

礼品卡余额不够付这一笔，多半是账单地址不在 Oregon，$19.99 被加了销售税。**不用绑卡，把账单地址改成 Oregon 就能用余额付。**

来源 A 记录的读者实例（2026-10-22）：$20 礼品卡已充进美区 Apple ID，升级时提示「必须提供付款信息才能继续购买。请登录你的 Apple 账户，然后点『账单信息』，以提供付款信息」，点「继续」后进了「添加付款方式」。把账单地址改成 Oregon，城市、邮编和电话一起换成 Oregon 的之后，用 $20 余额付成功了。

为什么会这样：

- Apple 按账单地址加收销售税。$20 付完 $19.99 只剩 $0.01，加了税，余额就不够了。
- 余额不够付全额时，Apple 会从你的主要付款方式扣费（[Apple 扣费规则](https://support.apple.com/zh-cn/118244)）。付款方式选的是 None，没有可扣的，就提示你先提供付款信息。

怎么处理：

1. 先看余额在不在这个 Apple ID 上：App Store → 右上角头像，有余额的话金额显示在名字下面（[查看余额](https://support.apple.com/zh-cn/119902)）。没有显示，说明礼品卡兑换到了别的 Apple ID。
2. 改账单地址：在 [account.apple.com](https://account.apple.com) 打开「付款与配送（Payment & Shipping）」，Payment Type 仍选 None，State 选 **Oregon（OR）**，City 和 ZIP 填 Oregon 的城市和对应邮编，电话也用 Oregon 的。用 iPhone 改：设置 → 你的姓名 → 付款与配送 → 编辑（[官方说明](https://support.apple.com/zh-cn/118293)）。
3. 回 iOS 版 ChatGPT App 重新点 Upgrade，付款前确认总额是 $19.99。
4. 不想改地址的话，再兑换一张礼品卡，让余额够付含税的总额。
5. 余额够、地址也改了还是弹：Apple 写过，有些购买即使用余额付，也可能要求账户里登记一张信用卡（[礼品卡和余额能买什么](https://support.apple.com/zh-cn/118245)）。这种情况按 Apple 对该账户的要求处理或联系 Apple 支持，不要填写虚假资料。

## 弹出「Your Purchase Could Not Be Completed / 购买未完成」

来源 C 的记录：付款时如果出现 `Your Purchase Could Not Be Completed`，通常说明 Apple 账户触发了购买风控，新注册的账号更容易遇到。原作者当时参考了一篇[购买失败处理教程](https://zhuanlan.zhihu.com/p/1987246308558403449)，通过 Apple 支持的「无法完成购买」入口联系人工客服核查购买权限，问题得到解决。

处理要点：先别反复点付款；通过 Apple 支持入口联系人工客服核查购买权限。原教程记录于 2026-11-09，当前可用性尚未重新验证。

## 付款后仍显示 Free？

1. 先核对 ChatGPT 登录账号和登录方式。
2. 到 App 内的 Settings → **Restore purchases** 恢复购买；这是 [OpenAI 官方的排查步骤](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)。
3. 仍失败时用 Apple 收据向 OpenAI 支持说明，不要立即再买一份。

详见 [付款后没到账怎么办](./subscription-not-active.md)。

## 其他常见问题

**Q：chatgpt.com 网页端的 Apple Pay 能用礼品卡余额吗？**
A：不能。Apple 余额的用途是 App Store 里的 App、内购和订阅等，不包括其他网站。网页结账里的 Apple Pay 用的是钱包里的银行卡（来源 A）。

**Q：怎么取消 Apple 订阅？**
A：设置 → Apple 账户 → 订阅 → ChatGPT → 取消订阅。如果没有取消按钮，但页面已经显示到期日期，通常说明自动续费已经关闭。只删除 App 不会取消订阅。

**Q：少数情况下余额足够，Apple 仍要求付款方式？**
A：以实际提示为准，按 Apple 对该账户的要求处理（来源 D）。

**Q：这条路线能订 Claude 吗？**
A：能。Claude 等有 iOS 端的产品都可以通过这个方法订阅（来源 W）。Claude 风控更严格，新账号建议先使用一段时间再订 Pro，见 [Claude iOS 订阅](../claude/subscribe-ios.md)。

## 相关教程

- [注册美区 Apple ID](../guides/apple-id-registration.md) · [Apple ID 改区](../guides/apple-id-region-change.md)
- [礼品卡购买](../guides/apple-gift-card-pockyt.md) · [兑换与排查](../guides/apple-gift-card-redemption.md)
- [续费、取消与退款](./renewal-and-refund.md)
- [Plus 和 Pro 怎么选](./plus-vs-pro.md)

礼品卡、改区流程对你来说太繁琐？先读[第三方订阅风险与挑选标准](./third-party-subscription.md)，了解红线后再决定是否改用第三方服务。

---

## 来源与修改说明

- 来源仓库：[chatgpt-plus-codex-cn-guide](https://github.com/cabbagecabbage/chatgpt-plus-codex-cn-guide)（cabbagecabbage，CC BY-NC-SA 4.0，已获商业授权，第五、八章）；[chatgpt-plus-subscription-guide](https://github.com/daydayup-xq/chatgpt-plus-subscription-guide)（daydayup-xq，CC BY 4.0，方法二）；[chatgpt-plus-china-guide](https://github.com/Avarce/chatgpt-plus-china-guide)（Avarce，无许可证，经项目负责人确认授权，路线 C 兑换订阅、Oregon 排查、Pro IAP 提醒）；[GPTplusSub](https://github.com/laoma528/GPTplusSub)（laoma528，无许可证，经项目负责人确认授权，`apple-gift-card.html`）；[Way-to-ChatGPT-Plus](https://github.com/farion1231/Way-to-ChatGPT-Plus)（farion1231，Apache-2.0）。
- 修改情况：合并五个来源的 iOS 订阅步骤，保留各自实测细节与日期；Pro 档位名称按 2026 年现状表述并保留原记录说明；删除全部商家推广；内部链接改为本站相对链接。
- 图片来源：本篇不新增图片；退款记录与客服截图见 [续费、取消与退款](./renewal-and-refund.md)。
- 原教程记录日期：2026-11-09（C）、2026-09-10（D）、2026-11-12（A）、2026-11-14（L）、2025-06-20（W）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。