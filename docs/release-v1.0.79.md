## NS PRO v1.0.79

NodeSeek 非官方 Android 客户端，WebView 打开官网并本地注入 **Nodeseek Pro** 用户脚本，免装油猴。

### 本版更新

- **启动布局**：关闭 WebView 概览缩放（`loadWithOverviewMode`），避免冷启动时页面被错误缩放导致大半空白、列表沉底
- **滚动复位**：启动后重置 window 与 `#app` / `main` 等内部滚动容器，修复内容不在顶部的问题
- **顶栏保护**：移除全局 `svg { max-width: 100% }`，避免 Logo 与导航图标被压缩隐藏
- **viewport**：不再强制覆盖页面 viewport meta，仅补充 `viewport-fit=cover`
- **性能**：通知页 DOM 监听仅在通知路由下生效，减少首页加载时的布局抖动

### 客户端能力

- 打开官方 NodeSeek，页面与官网一致
- 应用内检查更新、下载并安装
- 首次安装引导、长按菜单（刷新 / 重载脚本 / 清除登录）
- 外链走系统浏览器

**Android 7.0+** · 安装包见下方附件 `NS-PRO.apk`

---

*基于 [GreasyFork Nodeseek Pro](https://greasyfork.org/zh-CN/scripts/567109-nodeseek-pro)，GPL-3.0。与 NodeSeek 官方无关。*
