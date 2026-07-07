## NS PRO v1.0.80

NodeSeek 非官方 Android 客户端，WebView 打开官网并本地注入 **Nodeseek Pro** 用户脚本，免装油猴。

### 本版更新

- **回退屏幕自适应**：移除 v1.0.75 引入的 `setupDisplayAdapt()` 及 `notifyDisplayChanged()`，与 v1.0.74 备份一致
- **全局 CSS 精简**：去掉 `box-sizing: border-box` 全局规则、正文 img/svg 强制缩放、`:root` 断点变量等 v1.0.75+ 新增样式
- **通知页样式隔离**：通知页修复 CSS 改为仅在 `/notification` 路由下动态注入，不再写入全局样式表
- **WebView 设置恢复**：`loadWithOverviewMode` 恢复为 `true`（与 v1.0.74 备份一致）

### 客户端能力

- 打开官方 NodeSeek，页面与官网一致
- 应用内检查更新、下载并安装
- 首次安装引导、长按菜单（刷新 / 重载脚本 / 清除登录）
- 外链走系统浏览器

**Android 7.0+** · 安装包见下方附件 `NS-PRO.apk`

---

*基于 [GreasyFork Nodeseek Pro](https://greasyfork.org/zh-CN/scripts/567109-nodeseek-pro)，GPL-3.0。与 NodeSeek 官方无关。*
