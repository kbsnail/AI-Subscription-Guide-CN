# ChatGPT Plus 怎么自己订阅？官网与官方 App 操作步骤

> 适用：符合 OpenAI 地区和付款条件（本人和发卡机构都在支持地区）的用户；以及想了解官方自助流程全貌的读者。
> 最后核对日期 2026-11-15。中国大陆不在官方支持地区名单里，换卡、改账单地址或找别人付款不会改变这项限制；没有海外卡的读者先看 [没有海外银行卡怎么订阅](./no-foreign-card.md)。

## 官网网页：从登录到核对账单

1. **确认登录账号。** 在浏览器打开 [chatgpt.com](https://chatgpt.com/)，登录要升级的账号。先点头像，进入「设置 / Settings」→「账单 / Billing」，确认没有正在生效的 Plus，也没有网页端已经在扣费的订阅。
2. **选择升级套餐。** 回到 ChatGPT，点头像或页面里的「升级套餐 / Upgrade Plan」，选择「Get Plus」。不要误选 Pro 或 API 额度。
3. **填写账单与付款资料。** 在结算页核对套餐、月付金额、税费、币种、下一次扣费日期，再填入属于受支持地区发卡机构的信用卡或借记卡。OpenAI 当前公布的网页通用方式是信用卡和借记卡，部分地区另有本地方式；中国大陆支付宝、微信并未列在网页方式里（[网页付款方式](https://help.openai.com/en/articles/10421635-multicurrency-billing)）。
4. **验证并核对订阅。** 完成银行要求的 3D Secure 等验证，不要在验证过程中关闭结算页。付款后回到同一 ChatGPT 账号，在「设置 → 账单」查订阅和收据；头像/套餐处应显示 Plus。

银行卡逐项填写与拒付处理见 [海外银行卡官网直付](../guides/international-card.md)；被拒时按 [付款失败排查](./payment-failed.md) 区分地区、发卡行、余额、账单资料和验证，不要盲目反复尝试。

## 官方 iPhone / Android App：谁扣钱就到谁那里管

1. **安装官方 App。** 从设备的正式应用商店安装官方 ChatGPT App（开发者为 OpenAI 或 OpenAI OpCo, LLC），登录准备开通的那个 ChatGPT 账号。先检查手机系统「订阅」列表及 ChatGPT 网页账单，确认没有别处仍在扣同一订阅。
2. **确认购买渠道。** 在 App 里点「升级 / Upgrade」，核对实际弹出的结算方。如果弹出 Apple App Store 或 Google Play 付款界面，订阅由该商店管理；如果跳到网页，就按网页账单路径处理。
3. **核对账号与含税金额。** 付款前再次确认当前 ChatGPT 账号、Apple/Google 商店账号、套餐和应付金额。买完回到 App 查看 Plus；若显示 Free，先在 App 的设置里尝试「恢复购买 / Restore purchases」，并检查自己是否登录了付款时的 ChatGPT 账号。

分设备完整教程：[iOS 订阅（含礼品卡路线）](./subscribe-ios.md) · [Android / Google Play 订阅](./subscribe-android.md)。

## 付款后找不到 Plus 时

1. 先查看收据上的结算方：OpenAI 网页、Apple 还是 Google。
2. 再核对 ChatGPT 登录邮箱和登录方式。若通过 Apple 登录时选过「隐藏我的邮箱」，可能看到 Apple 私密转发邮箱；按原来的「通过 Apple 继续」登录。
3. 确认不是登录错账号后，退出重登；App 内购可在设置里恢复购买。
4. **不要马上换平台再买一次，否则可能出现两份订阅。**

详细排查见 [付款后没到账怎么办](./subscription-not-active.md)。

## 以后从哪里取消

- 网页购买：ChatGPT 头像 → Settings → Billing → Cancel plan。
- Apple：iPhone「设置」→ 你的姓名 →「订阅」→ ChatGPT → 取消。
- Google：Play 商店 → 头像 →「付款和订阅」→「订阅」→ ChatGPT → 取消。

更完整的日期和退款区别见 [续费、取消与退款](./renewal-and-refund.md)。

## 常见问题

**Q：Plus 和 API 是一回事吗？**
A：不是。Plus 是 ChatGPT 会员，API 是开发者按使用量单独付费。购买 Plus 不会自动获得 API 余额。

**Q：手机订阅后，电脑能用吗？**
A：可以，前提是电脑和手机登录的是同一个 ChatGPT 账号。

**Q：可以在网页、Apple 和 Google Play 同时订阅吗？**
A：不建议。这样容易产生重复扣款。保留一条订阅路径就够了。

## 相关教程

- [海外银行卡官网直付](../guides/international-card.md)
- [iOS 订阅](./subscribe-ios.md) · [Android 订阅](./subscribe-android.md)
- [续费、取消与退款](./renewal-and-refund.md)
- [账号安全与付款前检查](../guides/account-security.md)

---

## 来源与修改说明

- 来源仓库：[GPTplusSub](https://github.com/laoma528/GPTplusSub)（laoma528，无许可证，经项目负责人确认授权，`self-subscribe.html`）；[chatgpt-plus-subscription-guide](https://github.com/daydayup-xq/chatgpt-plus-subscription-guide)（daydayup-xq，CC BY 4.0，FAQ 与开发者核对提醒）。
- 修改情况：保留官方自助流程全部步骤与官方帮助链接；删除原站 ProdClub 导流内容；内部链接改为本站相对链接。
- 图片来源：本篇无图片。
- 原教程记录日期：2026-11-14（L）、2026-09-10（D）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。
