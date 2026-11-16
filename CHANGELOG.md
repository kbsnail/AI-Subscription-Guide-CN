# 更新记录（CHANGELOG）

## 2026-11-16 · V3.0 定向内容优化（本地，未提交、未推送，待项目负责人验收）

仅处理任务书指定的三个问题（03 / 04 / 08），最小必要修改，保留原有结构、教程步骤、实测记录、截图与来源署名。

### 03 · Google Play 改区规则一致性

- `chatgpt/subscribe-android.md`：改区规则统一为 Google 官方口径——首次设置后至少 90 天才能更改、每次更改也需至少间隔 90 天，附官方帮助页链接（2026-11-16 核对）；补充 48 小时生效、余额随地区锁定、家人群组限制。
- `chatgpt/subscribe-huawei.md`：删除 FAQ 中「一年只能改一次」的错误表述，改为官方 90 天规则；文首新增历史实测适用范围提示（特定设备 / 系统 / 地区 / 银行卡条件；Play 地区由付款资料决定而非仅由节点 IP 决定；银联支持以地区付款页实际显示为准）。13 张截图与全部步骤未改动。

### 04 · 第三方代充表述去保证化

- `chatgpt/third-party-subscription.md`：文首新增利益披露（本站维护方同时提供独立第三方服务，非官方授权代理）；交付类型表扩充为自助代充 / 协助付款（需 Session 等凭据）/ 人工协助 / 兑换码 / 成品号 / 共享号；删除「靠谱平台几分钟到账」等无依据保证，交付时间与售后统一为「以购买时的商品说明、订单状态及商家披露条款为准」；来源 A 的 30 天质保保留为历史个案记录。商业服务入口按任务书保留。
- `chatgpt/subscription-methods.md`：成本对比表重建为客观维度（适用条件 / 操作难度 / 费用构成 / 交付方式 / 风险限制 / 教程），删除全部无依据的「隐私 / 稳定性 / 综合」评级；历史实测价格保留并标注日期。
- 同步修正：`chatgpt/no-foreign-card.md`、`chatgpt/subscription-not-active.md`、`chatgpt/faq.md`、`claude/payment-issues.md`、`guides/account-security.md`（掉订阅补偿表述与站内锚点一致）。

### 08 · 套餐价格、模型权益与额度信息

- `chatgpt/plus-vs-pro.md`：价格与档位结构对照官方 Codex 定价页核实（Free $0 / Go $8 / Plus $20 / Pro $100·$200·$500）；「约 10 / 20 / 50 倍」明确标注为 Codex 负责人 Tibo 的 X 说明而非官方定价页承诺；帮助中心链接更正为官方文档现行 slug。
- `claude/subscribe-official.md`：更名日期更正为官方公告日 2026-10-30（美国时间，北京时间 10-31，附 @claudeai 公告链接）；补充 Max 5 倍 / Ultra 每周 10 倍官方用量口径、Ultra 无 5 小时限制仅限已验证账户、Max $100 / Ultra $200 月度 API 额度（含领取条件、适用范围与不结转规则，按官方帮助中心 17154008 核对）、仅月付、官方退款 FAQ。同步 `claude/README.md`、`claude/subscription-methods.md`（Pro 年付价格）、根 README 一行、`chatgpt/faq.md` 更名日期。
- `codex/model-selection.md`：文首区分官方当前推荐名单（GPT-6 Astra / GPT-6.1 Sol / GPT-6.1 Terra / GPT-6 Luna，2026-11-16 按官方模型文档核对）与原作者历史三档推荐；IQ 评分补充「第三方测试，不代表 OpenAI 官方性能评级」声明；「不推荐 GPT-6 Luna」标注为原作者个人结论并附官方定位对照；退役模型保留为历史。
- `codex/usage-and-limits.md`：文首新增历史样本声明（2026 年 3–8 月统计、140 元实付与 150 美元估算两个假设，非官方当前额度、非现金价值）与当前官方额度口径（Plus 每 5 小时估算区间、Pro 无五小时限制、用量面板入口）；「20x Pro」标注为旧称（现 Pro 200），理论倍数标注为 Tibo 说明。3–7 月 45 倍统计、公式、数据表与使用记录全部保留未改动。
- Codex 降智专题（`codex/troubleshooting.md`）的实验方法与机制解释按任务书未改动。

### 检查

- 自动检查：断链 0、失效锚点 0、缺失图片 0、重复 H1 0、敏感信息 0；UTM / 服务锚点 / 目录锚点 / H1 约定全部通过。forbidden 命中 45 处均为「来源与修改说明」中描述已删除推广的元信息（较上次 +1 为新增修改说明文字），internal_paths 7 处为 CHANGELOG / SOURCES 对工作区目录的说明，均属已知豁免。

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