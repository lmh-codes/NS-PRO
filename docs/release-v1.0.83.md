## NS PRO v1.0.83

NodeSeek 非官方 Android 客户端，WebView 打开官网并本地注入 **Nodeseek Pro** 用户脚本，免装油猴。

### 本版更新

- **上半屏黑屏**：修复冷启动时列表滚动位置被误恢复（`sessionStorage` 快照 + 任意 `popstate` 触发）
- **滚动复位**：新增列表页启动复位，重置 window 与 `#app` / `main` 等内部滚动容器
- **WebView 缩放**：关闭 `loadWithOverviewMode`，避免首屏视口缩放导致内容沉底
- **背景同步**：移除 `header_guard` 过早设置深色 WebView 背景（加剧黑屏观感）

### 客户端能力

- 打开官方 NodeSeek，页面与官网一致
- 应用内检查更新、下载并安装
- 首次安装引导、长按菜单（刷新 / 重载脚本 / 清除登录）
- 外链走系统浏览器

**Android 7.0+** · 安装包见下方附件 `NS-PRO.apk`

---

*基于 [GreasyFork Nodeseek Pro](https://greasyfork.org/zh-CN/scripts/567109-nodeseek-pro)，GPL-3.0。与 NodeSeek 官方无关。*
