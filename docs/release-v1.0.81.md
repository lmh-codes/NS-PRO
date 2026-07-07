## NS PRO v1.0.81

NodeSeek 非官方 Android 客户端，WebView 打开官网并本地注入 **Nodeseek Pro** 用户脚本，免装油猴。

### 本版更新

- **冷启动闪屏**：首屏不再在 `onPageCommitVisible` 过早显示 WebView，改为等 DOM / Pro 脚本就绪后再 reveal
- **加载指示**：冷启动期间保持顶部进度条，避免半黑空白页暴露约 1–2 秒
- **背景同步**：`header_guard` 在 body 出现时同步页面深浅色背景，减少黑/白闪烁

### 客户端能力

- 打开官方 NodeSeek，页面与官网一致
- 应用内检查更新、下载并安装
- 首次安装引导、长按菜单（刷新 / 重载脚本 / 清除登录）
- 外链走系统浏览器

**Android 7.0+** · 安装包见下方附件 `NS-PRO.apk`

---

*基于 [GreasyFork Nodeseek Pro](https://greasyfork.org/zh-CN/scripts/567109-nodeseek-pro)，GPL-3.0。与 NodeSeek 官方无关。*
