# Android 怎么通过 Google Play 订阅 ChatGPT Plus？

> 适用：Android 手机能够正常使用 Google Play，并且已经有 Play 支持的付款方式的用户。
> 核心步骤来自 chatgpt-plus-subscription-guide（2026-09-10 核对）；最后核对日期 2026-11-15。
> 华为手机没有 Google Play？看 [华为手机银联订阅路线](./subscribe-huawei.md)。

## 可选：单独注册一个 Google 账号

如果不想改动平时使用的 Google Play 账号，可以新建一个专门负责 ChatGPT 付款的 Google 账号：

1. 进入 [Google 账号注册页面](https://accounts.google.com/signup)。
2. 选择「为我自己创建」。
3. 填写姓名、出生日期和基本信息。
4. 选择新的 Gmail 地址，或者使用现有的非 Gmail 邮箱。
5. 设置密码，并按页面要求完成验证。
6. 添加恢复手机号和恢复邮箱。
7. 在 Android 手机的系统设置或 Google Play 中添加这个账号。
8. 进入 Google Play，切换到新账号。
9. 添加付款方式，再按下方步骤订阅 ChatGPT。

**新建 Google 账号不会自动获得某个国家或地区的 Play 资料。** Play 地区仍取决于实际所在地以及添加的付款资料。以后取消订阅和查看 Google Play 收据时，也必须切回这个账号。

## 订阅操作步骤

1. 进入 Google Play，确认当前 Google 账号。
2. 搜索 ChatGPT，确认开发者是 **OpenAI**（[官方应用](https://play.google.com/store/apps/details?id=com.openai.chatgpt)）。
3. 进入头像 →「付款和订阅」→「付款方式」。
4. 添加当前 Play 地区支持的银行卡或其他付款方式。
5. 进入官方 ChatGPT App，登录准备升级的 ChatGPT 账号。
6. 在设置里选择 Plus。
7. 在 Google Play 付款窗口核对 Google 账号、套餐、金额和币种。
8. 完成付款验证。
9. 回到 ChatGPT 确认 Plus。
10. 再到 Google Play 的「订阅」中确认续费日期。

## Google Play 地区不对怎么办？

查看路径：

`Google Play → 头像 → 设置 → 常规 → 账号和设备偏好设置 → 国家/地区和个人资料`

如果你有新地区的长期使用条件，可以按页面提示建立对应地区的付款资料。实操中，**网络所在地区、Play 地区、付款资料和账单地址需要尽量一致**，只改其中一项通常解决不了支付问题。

Google 官方要求用户实际位于新地区，并使用该地区可用的付款方式。按官方说明：**首次设置国家/地区后至少 90 天才能更改，之后每次更改也需至少间隔 90 天**（某些情况下还有额外限制；家人群组成员无法自行更改）。这不是「每 90 天都能随意换区」的保证。更改最多需要 48 小时生效；原地区余额不会自动转移，改回原地区后才能继续使用（[Google Play 更改国家或地区](https://support.google.com/googleplay/answer/7431675?hl=zh-Hans)，2026-11-16 核对）。

社区教程里常见用地址生成器补齐地区资料。它只能提供符合格式的地址，不能替代当地付款方式，也不能保证通过 Google 的付款验证。

> 国内银联储蓄卡 + 新加坡区 Play 的实测路线见 [华为手机订阅教程](./subscribe-huawei.md)；该路线对节点和账号地区有硬性要求，先读准备条件。

## 怎么取消 Google Play 订阅

`Google Play → 头像 → 付款和订阅 → 订阅 → ChatGPT → 取消订阅`

**只卸载 ChatGPT App 不会取消续费。** 取消后当期仍可用到期，详见 [续费、取消与退款](./renewal-and-refund.md)。

## 常见问题

**Q：扣款是人民币还是外币？**
A：按 Play 商店地区计价。例如新加坡区按新币（SGD）计价，银联通道会自动换汇成人民币扣款，汇率按扣款当日银联牌价，会有小幅汇率差（来源 Y）。

**Q：付款失败可以一直重试吗？**
A：不建议。先查银行或付款平台的拒绝原因，再重试。连续提交可能产生多笔预授权或授权失败费（来源 D）。

## 相关教程

- [华为手机 + 国内银联卡路线](./subscribe-huawei.md)
- [订阅方式总览](./subscription-methods.md)
- [付款失败排查](./payment-failed.md)
- [网络环境要求](../guides/network-environment.md)

---

## 来源与修改说明

- 来源仓库：[chatgpt-plus-subscription-guide](https://github.com/daydayup-xq/chatgpt-plus-subscription-guide)（daydayup-xq，CC BY 4.0，方法三全部步骤与官方链接）；[chatgpt-yinlian-chongzhi](https://github.com/CZGPT/chatgpt-yinlian-chongzhi)（CZGPT，无许可证，经项目负责人确认授权，FAQ 汇率说明）。
- 修改情况：保留原步骤与 Google 官方规则说明；删除 D 来源的抖音导流章节；内部链接改为本站相对链接。2026-11-16 按 Google 官方帮助页核对并细化改区 90 天规则表述。
- 图片来源：本篇无图片（华为路线截图见专篇）。
- 原教程记录日期：2026-09-10（D）、2026-08（Y）；本整合核对日期：2026-11-15。原教程记录于上述日期，当前可用性尚未重新验证。
