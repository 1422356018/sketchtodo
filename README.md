# ✏️ Todo Cards · 手绘风待办看板

> **Excalidraw 风格的手绘待办应用** — 不规则圆角边框、蜡笔实色阴影、毛玻璃壁纸、支持 Pixiv 二次元壁纸系统。

---

## ✨ 特色

| 特性 | 说明 |
|:---|:---|
| 🎨 **手绘风UI** | Excalidraw 启发的不规则圆角边框 + 蜡笔实色阴影 + 卡片微旋 |
| 🖌️ **手写字体** | ZCOOL KuaiLe（中文）、Long Cang、Caveat（英文）全栈手写体 |
| 🖼️ **毛玻璃壁纸** | Pixiv画师作品做壁纸，`backdrop-filter: blur(18~28px)` 毛玻璃效果 |
| 📦 **纯前端** | 单 HTML 文件，零依赖，打开即用 |
| 💾 **localStorage 持久化** | 像 Excalidraw 一样简单 — 自动保存，手动导出/导入 JSON |
| 🖱️ **拖拽管理** | 三栏看板（待办/进行中/已完成），纯拖拽改变状态 |
| ✏️ **双击编辑** | 双击任意卡片即可修改标题、备注和时间 |
| 📤 **导出/导入** | 一键导出 JSON 备份，支持导入恢复 |
| 🤖 **AI远程管理** | AI 写入 `data.js`，刷新页面自动同步任务 |

## 🚀 快速开始

1. 下载 `index.html`
2. 用浏览器（推荐 Edge/Chrome）打开
3. 开始管理你的任务！

> *首次打开为空看板，点击「＋ 新任务」添加你的第一张卡片。*

## 🎨 壁纸系统

- 自动检测本地图片（支持 PNG/JPG）
- 点击工具栏 **🎨 壁纸** 按钮选择 / 随机切换
- 浏览器记住你的壁纸偏好

## 🗂️ 项目文件

| 文件 | 说明 |
|:---|:---|
| `index.html` | 主程序（单文件，全部代码） |
| `data.js` | AI 远程管理用数据文件 |
| `data.json` | JSON 格式数据备份 |
| `pixiv12.ico` | 项目图标 |

## 🛠️ 技术栈

- 纯 HTML + CSS + JavaScript（零依赖）
- Class-based 架构
- 手绘 CSS 技巧：`border-radius: 255px 15px 225px 15px/15px 225px 15px 255px`
- 毛玻璃效果：`backdrop-filter: blur()` + 半透明白底
- localStorage 持久化

## 🙏 借鉴与致谢

本项目在架构与风格上借鉴了以下开源项目：

| 项目 | 借鉴内容 |
|:---|:---|
| **[Excalidraw](https://github.com/excalidraw/excalidraw)** | 手绘风格UI灵感 — 不规则圆角边框、蜡笔实色阴影、卡片微旋等CSS技巧 |
| **[kards](https://github.com/nicedoc/kards)** | Class-based 架构设计 — TodoItem / TodoBoard / Renderer / DragDropManager 的分层模式 |

**🤖 AI 辅助声明**：本项目由 **Hermes Agent**共同完成。从架构设计、UI风格实现到数据同步方案，全程通过自然语言对话协作开发。

**👨‍💻 关于作者**：开发者无任何专业开发经验，仅凭兴趣偶然入坑，一边学习基础一边摸索实践。这个项目是学习路上的一小块里程碑，还有很多不足，欢迎指点交流 🙇

**前人栽树，后人乘凉。** 感谢这些优秀的开源项目带来的启发。

## 📜 许可证

MIT © [1422356018](https://github.com/1422356018)
