# ChatGPT 付款失败、银行卡被拒怎么办？按提示分类处理

> 适用：在 ChatGPT 官网或 App 付款被拒、提示错误、或扣款后没看到 Plus 的用户。
> 最后核对日期 2026-11-15。**银行卡被拒，不要盲目换卡：先看是哪一类错误。**

## 先分清：付款失败和地区不支持是两件事

ChatGPT 银行卡付款失败，先查本人和发卡行是否符合 [OpenAI 支持地区](https://help.openai.com/en/articles/7947663-chatgpt-supported-countries) 条件；中国大陆不在名单中，国内银行发行的双币 Visa、Mastercard 卡也不支持官网直付。符合条件的海外卡再查余额、账单资料、银行限制与 3D Secure 验证。已经扣款却没看到 Plus 时，先核对收款平台和原账号，不要立刻重买。

若页面明确提示所在地区不受支持，先按 [没有海外银行卡怎么订阅](./no-foreign-card.md) 判断，不要把网络或地址伪装当成能保证解决的步骤。

## 按你看到的情况处理

| 你看到的情况 | 现在怎么做 |
| --- | --- |
| 中国大陆地区或国内银行发行的卡被拒 | 先停止反复试卡。OpenAI 要求所在地和发卡机构都在支持地区；换账单地址不会改变真实发卡地区。改走 [礼品卡路线](../guides/apple-gift-card-pockyt.md) 或了解 [第三方服务风险](./third-party-subscription.md) |
| 受支持地区的卡提示「付款被拒」 | 核对卡号、有效期、CVC、真实账单地址及余额；确认银行允许网上、国际和周期性付款。资料正确仍拒时联系发卡行问是否拦截了这笔交易 |
| 提示「需要验证」或 3D Secure 失败 | 不要关掉银行跳转或验证码页面。允许验证弹窗，完成银行 App/短信确认；仍失败可换浏览器无痕窗口，联系发卡行确认 3DS 已启用 |
| 已经扣款，但仍显示 Free | 先找付款收据，确认由 OpenAI、Apple、Google 还是第三方扣费；再确认登录的是原 ChatGPT 账号。App 内购在设置中尝试恢复购买。不要立即再付一笔，见 [付款后没到账](./subscription-not-active.md) |
| 第三方代充已付款，订单仍待确认 | 回到原订单页等自动确认，别另开订单或再次付款。持续不变时带订单号、付款时间和不含登录凭据的凭证联系商家客服 |
| iOS 内购提示「必须提供付款信息才能继续购买」 | 用礼品卡余额付时最常见的原因是账单地址不在免税州，$19.99 加税后超过 $20 余额。不用绑卡，改账单地址就行，见 [iOS 订阅教程排查段](./subscribe-ios.md#付款时提示必须提供付款信息才能继续购买) |
| iOS 弹出「购买未完成 / Your Purchase Could Not Be Completed」 | Apple 购买风控，新注册账号更容易遇到。先别反复点，通过 Apple 支持入口联系人工客服，见 [iOS 订阅教程](./subscribe-ios.md#弹出your-purchase-could-not-be-completed--购买未完成) |

## 还没到支付页就打不开 / 转圈

来源 A 的排查经验：

- **点了「Upgrade」没反应、Stripe 弹窗一直加载：** 多半是节点带宽小、丢包高，Stripe 的脚本没加载全，或浏览器缓存了上次的失败状态。换一个稳定的美区节点、开无痕、清一下缓存重试。
- **提示 Country not supported：** 你的网络出口落在了不支持的地区。把出口切到美 / 英 / 新 / 日 / 加等支持地区，并且别频繁在不同国家之间跳。
- **判断要点：** 这一阶段的问题基本都是网络问题，跟你的卡没关系，别急着换卡。

## 受支持地区的自助付款，可再做这三步

来源 L 的自助排查顺序：

1. **检查浏览器与验证弹窗。** 关闭可能干扰付款跳转的广告拦截，清理浏览器缓存和 Cookie 后重新打开原结算流程。
2. **查看银行拒付记录。** 看银行 App、短信或卡管理页面有没有拒绝记录；联系发卡行时说明是在线、国际、周期性订阅交易，询问是否要放行或完成 3D 验证。
3. **联系 OpenAI 支持。** 若银行确认没有拦截、账号和地区均符合官方条件，再通过 [OpenAI 帮助中心](https://help.openai.com/) 联系支持，并提供错误文字和付款时间；**不要提供完整卡号**。

OpenAI 对 3D Secure 失败的补充办法（来源 A 引官方）：允许弹窗和页面跳转、关掉广告拦截插件，用隐私模式或换浏览器、设备、网络再试；在银行短信或 App 里确认时，不要关闭或刷新结账页。还不行，请发卡银行为网上、境外交易开通 3D 验证，或者换一张卡。

## 其他常见提示

- **Something went wrong, please try again later：** 常见于同一 IP 短时间内多次尝试、或卡段已被标记（来源 A 的经验判断）。别硬刚，换个思路（礼品卡 / 靠谱第三方）比在这里死磕划算。
- **付款失败可以一直重试吗？** 不建议。先查银行或 VCC 平台的拒绝原因，再重试。连续提交可能产生多笔预授权或授权失败费（来源 D）。重试越多，越容易给账号累加风控分（来源 A）。

## 官方参考

- [Why was my credit card declined?](https://help.openai.com/en/articles/7232916-why-was-my-credit-card-declined)
- [Troubleshooting ChatGPT Plus or Pro renewal payments](https://help.openai.com/en/articles/7242622-troubleshooting-chatgpt-plus-or-pro-renewal-payments)
- [What is ChatGPT Plus?（扣款后仍是 Free）](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)
- [ChatGPT 支持国家和地区](https://help.openai.com/en/articles/7947663-chatgpt-supported-countries)

## 相关教程

- [海外银行卡官网直付](../guides/international-card.md)
- [付款后没到账怎么办](./subscription-not-active.md)
- [iOS 订阅排查](./subscribe-ios.md)
- [网络环境要求](../guides/network-environment.md)

按症状排查后仍无法付款、不想继续折腾？先读[第三方订阅风险与挑选标准](./third-party-subscription.md)，了解红线后再决定是否改用第三方服务。

---

## 来源与修改说明

- 来源仓库：[GPTplusSub](https://github.com/laoma528/GPTplusSub)（laoma528，无许可证，经项目负责人确认授权，`payment-failed.html`）；[chatgpt-plus-china-guide](https://github.com/Avarce/chatgpt-plus-china-guide)（Avarce，无许可证，经项目负责人确认授权，附录三阶段排查）；[chatgpt-plus-subscription-guide](https://github.com/daydayup-xq/chatgpt-plus-subscription-guide)（daydayup-xq，CC BY 4.0，重试提醒）。
- 修改情况：合并症状表与自助步骤；将 ProdClub 专属订单行泛化为「第三方代充订单」并删除导流链接；补充 iOS 两类提示的本站链接；保留全部 OpenAI 官方帮助链接。
- 图片来源：本篇不新增图片；$0 试用被拒截图见 [订阅方式总览](./subscription-methods.md)。
- 原教程记录日期：2026-11-14（L）、2026-11-12（A）、2026-09-10（D）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。
