# 更新记录（CHANGELOG）

## 2026-11-15 · 决策点中立指引（方案 A）

- 经项目负责人确认，在 5 个「放弃自助」决策点文章文末新增指向第三方风险专篇的中立指引（不含直接服务链接与 UTM）：no-foreign-card、payment-failed、subscription-not-active、subscribe-ios、virtual-card。
- README 声明同步：其余教程正文不含商业推广，仅少数文末提供指向风险专篇的中立指引。

## 2026-11-15 · 首次公开发布

- 经项目负责人确认（来源授权齐全、截图可发、邮箱已删），仓库首次推送至公开 GitHub：<https://github.com/kbsnail/AI-Subscription-Guide-CN>（main 分支，135 个文件）。

## 2026-11-15 · Claude 来源授权确认

- pwna11/ClaudePro、ai-subscriber/claude-subscribe-guide 取得作者本人许可（经项目负责人确认）：SOURCES 状态由「待确认」更新为「已确认」，README 简介改为 12 个已获授权来源，claude 栏目 3 篇文章文末来源说明同步更新。
- tomridder 仓库仍不整合为教程；如后续引用其通用知识需单独确认授权。
- 按项目负责人要求删除两处邮箱：SOURCES 中 pwna11 的 git 提交占位邮箱、Pockyt 教程中的商家客服邮箱（改为「通过其官网联系」）。敏感信息检查命中降为 0。
- 项目负责人确认 87 张已打码截图可随内容发布（SOURCES 待确认清单第 2 项关闭）。

## 2026-11-15 · 第二阶段验收优化 V2.1（本地，未推送公开 GitHub）

- README 新增首屏「开通 AI 会员：两种方式」双路径入口（自助教程总览 + 第三方服务 UTM 入口，附独立第三方简短声明）；底部「服务与声明」保留完整说明并更新入口位置清单。
- 快速问题导航拆分支付宝场景：支付宝买 Apple 礼品卡 → Pockyt 教程；第三方订阅 → 第三方风险教程（10 行 → 11 行，链接目标不变）。
- 订阅方式对比表修订：iOS 价格改为以 App Store 实际结算为准；Apple 账号关联改为「可能形成关联、跨账号恢复受限」的非绝对表述；Google Play / 华为银联标注为特定条件实测、需按实际账户核实；官网支付条件以 OpenAI 官方政策与结算页为准；虚拟卡行注明已停运平台不再可用。
- SOURCES 授权状态核查：明确第一批 10 个来源已确认、第二批 Claude 2 个来源待确认（首批确认不覆盖第二批，工作区无第二批授权记录），不虚构授权。
- 本次仅修改 README.md、SOURCES.md 与本 CHANGELOG；正文教程、图片与目录结构未改动。

## 2026-11-15 · 第二阶段：内容整合完成（本地，未推送公开 GitHub）

### 新增

- 产品栏目与公共教程共 **35 篇正文 + 5 个栏目导航**：
  - `chatgpt/` 13 篇：订阅方式总览、无海外卡直答、注册与付款前检查、套餐选择、官网 / iOS / Android / 华为订阅、付款失败、未到账、续费退款、第三方风险、FAQ。
  - `claude/` 4 篇：官方订阅（含 2026-10-31 Max→Max / Max 20x→Ultra 更名更新）、方式总览、iOS 礼品卡、充值问题。
  - `codex/` 5 篇：开通与二次验证申诉实录、Windows 安装、模型选择、周额度与中转性价比、降智自测。
  - `guides/` 12 篇：Apple ID 注册 / 改区、Pockyt / SEAGM / 官网买卡、礼品卡兑换、海外卡、虚拟卡、账号安全、网络环境、历史支付归档、土耳其历史记录。
  - `other-tools/` 1 篇：API 中转与客户端配置。
- 复用并打码图片 **87 张**（chatgpt 20 / codex 7 / guides 54 / other-tools 6），逐张来源登记于工作区 `phase2/image-mapping.json`（不公开）。
- 根 README 重写为七部分首页（快速问题导航、按产品进入、方式对比、全部教程目录、服务与声明、来源与许可）；SOURCES.md 更新为第二阶段授权状态；新增本 CHANGELOG。
- `licenses/` 保留 4 份来源许可证文本（Apache-2.0、MIT、CC BY-NC-SA 4.0、CC BY 4.0）。

### 变更与整合决策

- 目录由第一阶段占位分类（01–07）重构为产品优先结构：`chatgpt/ claude/ codex/ guides/ other-tools/ assets/`；公共教程单一权威版本，产品页链接复用。
- 重复内容按「取质量更高版本、互补合并」处理：Apple ID 注册合并 W+D+A+S；iOS 订阅合并 C+D+A+L+W；FAQ 按问题合并 A/D/L/W/S 并保留独有问题。
- 不同支付路线保持独立成篇：Pockyt / SEAGM / Apple 官网 / 注册 / 改区 / 兑换 / iOS 内购。
- 时效更新：ChatGPT 2026 套餐表与 Pro 档位变化（9-29 / 10-29）、Claude 套餐更名（10-31）、WildCard（2025-07-12）与 Depay/Dupay（2025-11-30）失效标注。
- 历史化降级：G/O 的 Depay 路线与 W 土耳其低价区仅作历史归档 / 待核查记录，不含可执行失效步骤。

### 移除（不随内容复用）

- 全部来源商业推广与返利链接：AONIR utm、抖音导流、czgptai.com、store.ai-headshot.net、cnouyi.care / Depay 邀请码 / Vultr 推荐、zz-api.cc.cd aff、claudepro.org、claude.sub-ai.cc、ProdClub 邀请链接 / 优惠码 / 下载镜像。
- L 来源的 Session 获取与提交操作步骤（敏感凭据方法），仅保留概念与风险警告。
- N01 灰产内容不整合；tomridder 成品号销售页不整合为教程。
- S01 的 3 张失效外链图与 A01 的 5 张旧版未用图不复用。

### 安全与合规

- 截图打码：账单、邮箱、订单号、兑换码、客服姓名等；令牌截图仅保留原作者打码形式；不发布任何有效凭据。
- 每篇标注「原教程记录日期 / 本整合核对日期」，未验证内容统一标注「当前可用性尚未重新验证」。
- 商业入口仅限 README「服务与声明」、chatgpt 方式总览第三方说明、第三方风险一文；UTM 链接见 README。

### 待办（人工确认）

- Claude 两个已整合来源与 tomridder 仓库的书面授权确认（见 SOURCES 待确认清单）。
- 截图第三方界面权利的最终确认。
- 验收报告提交后，由项目负责人决定是否推送公开 GitHub（本阶段不推送）。

## 2026-11-15 · 第一阶段：来源扫描与规划

- 浅克隆 10 个来源仓库至工作区 `sources/`（只读快照）。
- 脚本扫描 Markdown 与图片，产出 `planning/content-inventory.md`、`content-mapping.md`、`duplicate-report.md`、`source-status.md` 与目标骨架（工作区内部资料，不公开）。
- 判定 N01 为订阅转移灰产不予整合；识别 G/O 过期、S01 外链图失效等待核查事项。