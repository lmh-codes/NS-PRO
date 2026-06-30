# NS PRO

NodeSeek 非官方 Android 客户端。WebView 打开 [NodeSeek 官网](https://www.nodeseek.com)，本地注入 Nodeseek Pro 用户脚本，免装油猴。

**Android 7.0+** · 当前版本 **v1.0.24**

## 下载

| 文件 | 说明 |
|------|------|
| [NS-PRO.apk（直链下载）](https://github.com/lmh-codes/NS-PRO/releases/download/v1.0.24/NS-PRO.apk) | 安装包 |

也可在 [Releases](https://github.com/lmh-codes/NS-PRO/releases/latest) 页面下载最新版。

## 功能

### 客户端

- 打开官方 NodeSeek，页面与官网一致
- 内置 Nodeseek Pro 脚本，无需安装 Tampermonkey / 油猴
- 页面顶部下拉刷新当前页
- 首次安装引导设置链接默认打开方式
- 长按页面打开菜单（刷新、重载脚本、清除登录等）
- 外链走系统浏览器

### 内置 Pro 插件（Nodeseek Pro）

用于增强 NodeSeek 论坛体验，主要能力包括：

- **基础功能**：自动签到、签到过期提醒、下拉加载 / 无限滚动、NodeImage 图床上传助手
- **互动增强**：快速评论、快捷键操作
- **阅读体验**：Callout 渲染、代码高亮、图片预览、等级标记
- **内容管理**：内容过滤、浏览历史
- **个性化**：可视化设置面板，各功能可独立开关；支持配置备份
- **辅助工具**：名望诊断、社交关系相关辅助等

打开 Pro 设置面板时，客户端会自动禁用下拉刷新，避免误触。

## 合作站授权

部分合作站（如图床等）需通过 NodeSeek 的 Connect 完成账号关联。若在 App 内授权不成功（例如一直转圈、提示成功但未登录、授权后页面异常等），请改用网页端操作：

1. 在浏览器打开 [NodeSeek 官网](https://www.nodeseek.com) 并登录
2. 进入 **设置**，找到 **关联网站**（或合作站相关入口）
3. **取消** 已与 NS PRO 关联的网站绑定
4. 仍在网页端重新发起 Connect，按提示完成授权
5. 授权成功后，再打开 App 使用合作站功能

网页端 Connect 与官网流程一致，通常比 App 内授权更稳定。完成一次网页授权后，App 内一般即可正常使用。

## 安装

1. 下载 `apk/NS-PRO.apk` 或从 [Releases](https://github.com/lmh-codes/NS-PRO/releases/latest) 获取
2. 在 Android 手机上允许安装未知来源应用
3. 安装后打开 **NS PRO** 即可使用

## 文档

- [论坛发布说明](docs/NS_PRO_论坛发布.md)

## 说明

- 本仓库仅发布 APK 与文档，不包含源代码
- 脚本版本随 APK 打包，不会自动从网络更新
- 官网内容不做修改，仅在 WebView 内注入用户脚本
- 与 NodeSeek 官方无关

---

*基于 [GreasyFork Nodeseek Pro](https://greasyfork.org/zh-CN/scripts/567109-nodeseek-pro)，GPL-3.0。*
