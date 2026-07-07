## NS PRO v1.0.84

NodeSeek 非官方 Android 客户端，WebView 打开官网并本地注入 **Nodeseek Pro** 用户脚本，免装油猴。

### 本版更新

- **上下黑边闪烁**：冷启动时延后 WebView 显示到 `onPageFinished`，首帧布局稳定后再 reveal
- **滚动复位时机**：移除启动后多次延时复位（正是「闪一下恢复」的来源），改为 reveal 前一次性复位
- **视口稳定**：`header_guard` 补充 `initial-scale=1.0`，WebView 设置 `textZoom=100`

### 客户端能力

- 打开官方 NodeSeek，页面与官网一致
- 应用内检查更新、下载并安装
- 首次安装引导、长按菜单（刷新 / 重载脚本 / 清除登录）
- 外链走系统浏览器

**Android 7.0+** · 安装包见下方附件 `NS-PRO.apk`

---

*基于 [GreasyFork Nodeseek Pro](https://greasyfork.org/zh-CN/scripts/567109-nodeseek-pro)，GPL-3.0。与 NodeSeek 官方无关。*
