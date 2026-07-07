## NS PRO v1.0.82

NodeSeek 非官方 Android 客户端，WebView 打开官网并本地注入 **Nodeseek Pro** 用户脚本，免装油猴。

### 本版更新

- **修复纯黑屏**：回退 v1.0.81 冷启动延后显示逻辑（WebView 长时间不可见导致全黑）
- **显示时机恢复**：与 v1.0.80 一致，在 `onPageCommitVisible` 正常 reveal
- **保留**：`header_guard` 背景色同步（不影响显示逻辑）

### 客户端能力

- 打开官方 NodeSeek，页面与官网一致
- 应用内检查更新、下载并安装
- 首次安装引导、长按菜单（刷新 / 重载脚本 / 清除登录）
- 外链走系统浏览器

**Android 7.0+** · 安装包见下方附件 `NS-PRO.apk`

---

*基于 [GreasyFork Nodeseek Pro](https://greasyfork.org/zh-CN/scripts/567109-nodeseek-pro)，GPL-3.0。与 NodeSeek 官方无关。*
