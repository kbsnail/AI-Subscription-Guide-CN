# 钱付了，ChatGPT 还是 Free 怎么办？付款后没到账排查

> 适用：已经在官网、App Store、Google Play 或第三方平台付款，但账号没有显示 Plus 的用户。
> 最后核对日期 2026-11-15。**先处理原订单 / 原订阅，不要重复购买。**

## 先说结论

「钱付了没到账」最常见的原因不是支付失败，而是：**充到了另一个 ChatGPT 账号**、**银行显示的只是预授权**、或**第三方订单还没完成交付**。按下面顺序排查，多数能自己定位。

## 第一步：确认到底扣款没有、谁扣的

1. 查找付款收据：搜索邮件中的付款收据，辨认商家是 OpenAI、Apple、Google 还是第三方平台。核对金额、日期和订单号，**不要只看银行短信**（来源 L）。
2. 银行短信里的「扣款」可能只是预授权，实际未入账；以收据和平台账单为准（来源 D）。
3. 收据是 OpenAI → 登录同一 ChatGPT 账号打开「设置 → 账单」；是 Apple → iPhone「设置 → 你的姓名 → 订阅」；是 Google → Play 商店「付款和订阅 → 订阅」；是第三方 → 打开下单邮箱里的订单链接看状态。

## 第二步：确认登录的是原账号

- 回到 ChatGPT，刷新并核对当前登录账号的**邮箱和登录方式**。用 Apple 隐藏邮箱、Google 与普通邮箱登录可能进到不同账号（来源 L）。
- 退出后重新登录原账号，再从个人头像进入设置查看套餐。**不要只看浏览器旧标签页的缓存显示**（来源 L、A）。
- 多账号的人很容易付错号：对一下你充的是哪个邮箱（来源 A）。

## 第三步：按付款渠道处理

### 官网网页付款

确认 Settings → Billing 里的订阅状态和收据。仍异常时联系 OpenAI 支持，附交易时间和错误文字，不发送完整卡号。

### Apple / Google 内购

1. 在 ChatGPT App 的 Settings → **Restore purchases / 恢复购买**（[OpenAI 官方排查步骤](https://help.openai.com/en/articles/6950777-what-is-chatgpt-plus)、[恢复购买说明](https://help.openai.com/en/articles/8346573-restoring-a-chatgpt-plus-or-chatgpt-pro-subscription-purchased-in-the-apple-app-store)）。
2. 到对应商店的订阅列表确认订阅是否存在、由谁管理。
3. 仍失败时用商店收据向 OpenAI 支持说明，不要立即再买一份。

### Apple 内购特有的坑：订阅充到了绑定的旧账号

首次 Apple 内购后，Apple ID 与当时的 ChatGPT 账号永久绑定。即使你换了 ChatGPT 登录账号、甚至删除了旧账号，再用同一个 Apple ID 付款，订阅仍会关联到旧账号。原作者就踩过「账号 1 已删除，付款仍关联到账号 1」的坑。详见 [账号安全与付款前检查](../guides/account-security.md#一个-apple-id-只能给一个-chatgpt-账号订阅永久绑定)。这种情况可以尝试向 Apple 申请退款，但原作者第二次申请被拒，不能指望退款兜底，见 [续费、取消与退款](./renewal-and-refund.md)。

### 第三方代充订单

来源 L 的订单处理经验（已泛化，适用于多数有订单体系的平台）：

1. **先找回原订单。** 搜索下单邮箱里的订单邮件（检查垃圾邮件箱）；仍用下单时的同一浏览器，平台首页可能列出未完成订单；找不到就准备订单号或付款截图，通过平台客服入口找回。**订单链接拿到的人可以操作这张单，别发给无关的人。**
2. **已付款但订单显示待付款：** 回到原订单页等收款确认（通常几十秒到几分钟），不要再点一次「提交订单」或重新扫码付第二笔。一直没变化，记下订单号、付款时间与金额，带这些信息找客服核对；可以提供**不含登录凭据**的付款截图。
3. **订单处理中 / 转人工：** 钱已付，先保留订单号等处理，不要再另下单。卡住较久联系客服，只提供订单号和可公开的错误提示。
4. **订单显示完成，ChatGPT 仍是 Free：** 按上面第一、二步核对账号与登录方式；确认无误后带订单号和账号套餐页不含凭据的截图联系客服，说明「订单已完成但原账号仍显示 Free」。

**保存这些就够了：订单号、下单邮箱、付款时间和金额、订单页公开状态。不要把 Session、密码、验证码或完整支付卡资料放进客服消息。**（来源 L）

> 部分平台要求提交 Session 等登录凭据才能开通。Session 是敏感登录凭据，本站不提供获取与提交教程；不愿提供凭据的用户请选择其他路线，见 [第三方订阅风险](./third-party-subscription.md)。

## 第四步：账号异常（deactivated）

来源 A 的区分：

- **充值前就被封的：** 多是网络 / 滥用 / 违规内容触发，可发邮件申诉但成功率不高。
- **充值后被封的：** 大概率跟黑卡、人工代充交号、或多人共享有关。
- **掉订阅 ≠ 封号：** 掉订阅只是权益消失，账号不受影响，重新开一次就好；封号是账号停用，数据清零。详见 [账号安全](../guides/account-security.md#掉订阅--封号)。

## 不想继续了：退款入口

- 官网 / Apple / Google：见 [续费、取消与退款](./renewal-and-refund.md)。
- 第三方平台：付款后尚未开通、订单页有「申请退款」按钮时在原订单提交；没有按钮带订单号找客服。以购买时的商品条款为准。

## 相关教程

- [付款失败排查](./payment-failed.md)
- [续费、取消与退款](./renewal-and-refund.md)
- [账号安全与付款前检查](../guides/account-security.md)
- [第三方订阅风险](./third-party-subscription.md)

---

## 来源与修改说明

- 来源仓库：[GPTplusSub](https://github.com/laoma528/GPTplusSub)（laoma528，无许可证，经项目负责人确认授权，`order-help.html`、`payment-failed.html`、`self-subscribe.html`）；[chatgpt-plus-codex-cn-guide](https://github.com/cabbagecabbage/chatgpt-plus-codex-cn-guide)（cabbagecabbage，CC BY-NC-SA 4.0，已获商业授权，绑定踩坑）；[chatgpt-plus-subscription-guide](https://github.com/daydayup-xq/chatgpt-plus-subscription-guide)（daydayup-xq，CC BY 4.0，FAQ 3）；[chatgpt-plus-china-guide](https://github.com/Avarce/chatgpt-plus-china-guide)（Avarce，无许可证，经项目负责人确认授权，附录阶段三）。
- 修改情况：将 ProdClub 专属订单流程泛化为通用第三方订单排查；**删除提交 Session 的具体操作步骤与全部商家导流链接**，仅保留凭据安全提醒；保留原作者踩坑实例。
- 图片来源：本篇无图片。
- 原教程记录日期：2026-11-14（L）、2026-11-09（C）、2026-09-10（D）、2026-11-12（A）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。
