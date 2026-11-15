# Windows 版 Codex 怎么安装？官方 .msix 安装包与签名核验

> 适用：想在 Windows 电脑（含骁龙等 ARM 机型）上安装官方 Codex / ChatGPT 桌面应用的读者。
> 最后核对日期：2026-11-15。原教程记录于 2026-11-13，当前可用性尚未重新验证。

## 先说结论

- Windows 版 Codex 随 **ChatGPT 桌面应用**分发：安装包名称 `OpenAI.Codex`，发布者 OpenAI，经微软商店签名，`.msix` 格式。
- 推荐直接从 **Microsoft Store** 或 [OpenAI 官方 Windows 应用文档](https://learn.chatgpt.com/docs/app/windows) 获取，不需要第三方下载镜像。
- 安装前后自己核对三件事：**下载来源、发布者、Windows 签名校验结果**。
- 体积参考：x64 约 930 MB，ARM64 约 1 GB。骁龙等 ARM 电脑请选择 ARM64 版本。

> 原教程通过第三方服务（ProdClub）的解析入口下载微软商店安装包。该入口属于第三方镜像服务，本文不采用；以下流程保留原教程的核验方法与故障处理，下载渠道改为官方入口。

## 获取安装包

1. 打开 Microsoft Store，搜索 ChatGPT / OpenAI Codex，进入官方应用页面安装；或
2. 打开 [OpenAI 官方 Windows 应用文档](https://learn.chatgpt.com/docs/app/windows)，按页面指引获取对应架构（x64 / ARM64）的安装包。

这个文件从哪来（原教程说明，适用于商店签名的 .msix 包）：

- **OpenAI 发布**：安装包名称为 OpenAI.Codex，发布者为 OpenAI。
- **微软商店签名**：与商店中的安装包相同，带有微软商店签名。
- **微软服务器传输**：商店下载由微软下载服务器传输到你的电脑，国内有下载节点。

## 下载后，自己核对这几项

| 核对项 | 怎么看 |
| --- | --- |
| 下载来源 | 在浏览器下载记录中查看实际下载地址，通常来自微软的 microsoft.com 域名 |
| 发布者 | 双击安装包，检查安装窗口是否显示「发布者：OpenAI」 |
| 签名校验 | Windows 安装时会验证包签名；文件被篡改会导致签名校验失败。**不要跳过签名错误继续安装** |

官方路线提供的是原版 `.msix` 包：不需要额外运行第三方 `.exe` 安装器，也不需要把 Codex 配置为第三方接口。

## 三步装好

1. **安装文件**：双击下载好的 `.msix`，核对发布者后点击「安装」。如出现允许更改的提示，确认是这次安装再继续。
2. **从开始菜单打开**：安装后，在开始菜单找到「ChatGPT」，Codex 在应用内（原教程记录于 2026-11，应用名称与入口以实际版本为准）。
3. **登录账号**：使用自己的 ChatGPT 账号登录。应用后续会自动更新。

登录时可能触发手机号二次验证，机制与应对见 [Codex 开通、二次验证与登录](./subscription-and-access.md)。

## 遇到这些情况怎么办

### 浏览器提示「不安全的下载」或「通常不会下载此文件」

原页面说明：部分微软下载地址使用 HTTP，可能触发浏览器提醒。先核对实际来源（应为 microsoft.com 域名），再决定是否选择「保留」；安装时继续检查发布者和 Windows 签名结果。来源不明或签名校验失败的文件不要安装。

### 双击没反应，或提示需要「应用安装程序」

系统可能缺少「应用安装程序」组件，精简版 Windows 较常见。可以用 PowerShell 安装：

1. 右键开始按钮，打开「终端（管理员）」；Windows 10 上可打开「Windows PowerShell（管理员）」。
2. 输入下面的命令和一个空格，再将下载好的文件拖进窗口，确认完整文件路径后按回车：

   ```powershell
   Add-AppxPackage -Path <拖入文件后自动生成的完整路径>
   ```

### 使用的是 Mac 电脑

请前往 [OpenAI 官网应用文档](https://learn.chatgpt.com/docs/app) 选择 Mac 下载入口。

## FAQ

**Q：一定要通过微软商店安装吗？**
A：商店是最直接的官方渠道。官方文档提供的 .msix 直链同样可用，关键是核对来源域名、发布者与签名。不要使用来路不明的第三方「安装器」。

**Q：ARM 电脑装哪个版本？**
A：骁龙等 ARM 架构电脑选 ARM64 版（约 1 GB）；常规 Intel / AMD 电脑选 x64 版（约 930 MB）。

**Q：安装后需要单独订阅 Codex 吗？**
A：不需要。用已有 Plus / Pro 的 ChatGPT 账号登录即可，Codex 额度随订阅提供，见 [Codex 开通与登录](./subscription-and-access.md)。

## 相关教程

- [Codex 开通、二次验证与登录](./subscription-and-access.md)
- [Codex 模型与推理强度选择](./model-selection.md)
- [Codex 降智自测与恢复](./troubleshooting.md)

---

## 来源与修改说明

- 来源仓库：[GPTplusSub](https://github.com/laoma528/GPTplusSub)（laoma528，无许可证，经项目负责人确认授权）。
- 原始文档：`codex-windows.html`《Windows 版 Codex 下载：官方安装包，不用打开微软商店》（内容更新 2026-11-13）。
- 修改情况：保留安装包来源说明、三项核验、三步安装、浏览器提醒与 Add-AppxPackage 故障处理、Mac 指引；**删除 prodclub.xyz 第三方下载镜像链接与 ProdClub 服务入口、回退到 OpenAI 服务器的镜像说明**，下载渠道改为 Microsoft Store 与 OpenAI 官方文档；补充二次验证链接。
- 图片来源：无（原页面无配图）。
- 原教程记录日期：2026-11-13；本整合核对日期：2026-11-15。原教程记录于 2026-11-13，当前可用性尚未重新验证。