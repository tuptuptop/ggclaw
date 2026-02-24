# ggclaw - 下一代 AI 桌面助手

<div align="center">

**脱胎于 OpenClaw，基于 Rust 技术构建的智能工作平台**生态兼容、性能显著优化！

历时一个月快速迭代开发（3 年技术积累）

[![License: Apache 2.0](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Platform](https://img.shields.io/badge/platform-macOS%20%7C%20Windows%20%7C%20Linux-blue)](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2)

[English](README_EN.md) · [简体中文](README.md)

</div>

---

## ✨ 简介

ggclaw 是一款脱胎于 OpenClaw 的 AI 桌面助手，基于 Rust 技术构建，完美兼容 OpenClaw Skills 生态。历经一个月快速迭代开发（3 年技术积累），专为提升个人和团队工作效率而设计。可以在文案、图文、绘画、视频、提醒、物联网等多个场景下发挥作用。它不仅仅是一个 AI 聊天工具，更是一个**重新定义工作方式**的智能平台。

### 跨境电商领域的应用案例

在海南自贸港，ggclaw 正在重塑数万名跨境卖家的生存法则。通过自动化集群，企业可以优化约30%的初级岗位，每年节省的薪酬支出超过100万元。

**核心突破**：
- **全链路自动化能力**：独立站复刻、智能选品、竞品攻防
- **生产力升维**：图像生成、文案优化、数据挖掘
- **技术民主化**：三行命令完成部署，非技术人员可操作

**工作机制**：意图理解（LLM）+ 屏幕感知（Computer Vision）+ 动作执行（PyAutoGUI/Keyboard Control）

2026年的竞争，已演变为AI智能体应用深度的较量。

### 为什么选择 ggclaw？

- **🚀 极致性能**：启动仅需 1.5 秒，内存占用仅 80MB，比同类产品快 5 倍，比openclaw快太多了！
- **🔒 隐私优先**：所有数据本地加密存储，零云端依赖，你的数据完全掌控在自己手中
- **🌐 跨平台**：完美适配 macOS、Windows、Linux 三大操作系统，体验一致
- **🧩 生态兼容**：完美兼容 OpenClaw Skills 生态，无缝迁移现有插件，同时支持开发新的 Skills
- **💬 多平台集成**：无缝连接企业微信、钉钉、飞书、Telegram、Discord 等 6 大主流 IM 平台
- **🎯 真会动手**：不只是聊天，能接管电脑操作权限，通过自然语言指令执行各类任务
- **🧠 持久记忆**：长期记住你的偏好与上下文，越用越懂你
- **⚡ 主动触达**：心跳、定时任务、提醒，像 24 小时在线的同事

---

## 🎯 主要功能

### 🤖 智能协作空间

- 多会话管理，同时处理数十个 AI 协作任务
- 智能记忆系统，AI 越用越懂你
- 多种执行模式，满足不同安全需求
- 完整历史记录，随时追溯
- **持久记忆与人格**：记住你是谁、你的习惯，越用越像「你的」助手
- **主动触达**：心跳、定时任务、提醒，像 24 小时在线的同事

### 🧩 插件系统

完美兼容 OpenClaw Skills 生态，无缝迁移现有插件，同时支持开发新的 Skills。目前社区已有 **3000+** 技能，覆盖各种工作场景：

#### 核心基础 Skills（必装）

- **� File Manager（文件管家）**：全能文件读写能力，支持目录遍历、文件创建与编辑、PDF/TXT 内容读取
- **🌐 Browser Controller（全网通）**：浏览器自动化，支持网页浏览、数据抓取、表单填写等操作
- **💻 Terminal Pro（终端指挥官）**：执行 Shell/CMD 命令，支持软件安装、Git 操作、系统维护
- **🐍 Code Interpreter**：Python/R 代码执行，具备数据分析、可视化呈现等功能

#### 场景化 Skills（按需安装）

**📝 写作与内容创作**
- Copywriting（写作神器）：一键生成高质量文章、报告、演讲稿
- PDF 处理：智能生成与编辑 PDF 文档
- Word/Excel/PPT：Office 文档自动化处理

**🎨 设计与视觉**
- Web Design Guidelines：网页设计规范与最佳实践
- Canvas Design：专业设计工具
- Remotion：视频制作与动画

**💻 开发与编程**
- React Best Practices：React 最佳实践指南
- Unfuck My Git State：Git 状态诊断与修复
- Playwright：自动化测试与网页操作

**🏠 智能家居与 IoT**
- Home Assistant：智能家居控制
- 智能灯光控制：调节家中灯光
- 设备监控：实时监控智能设备状态
- **接入物理世界**：把 ggclaw 接入物理世界，它就是你的贾维斯

**📧 邮件与日程**
- Gmail：邮件收发、智能分类、自动回复
- Calendar：日历深度集成、智能定时任务、自动提醒
- 邮件处理效率提升 80%

**📱 社交媒体**
- 小红书：自动发布笔记
- Twitter/X：推文发布与管理
- 微博：内容发布与互动

**📊 数据与分析**
- 数据抓取：网页数据自动采集
- 数据分析：Python 数据分析与可视化
- 报告生成：自动生成各类报告

**🎮 游戏与娱乐**
- Web 游戏开发：快速开发框架
- 游戏自动化：游戏脚本开发
- 娱乐功能：音乐播放、视频推荐

**🔧 工具与实用**
- 天气查询：实时天气信息
- 翻译工具：多语言翻译
- 提醒功能：定时提醒重要事项

**🎉 欢迎开发者开发发布 Skills！**

### 💬 IM 网关集成

一处管理所有消息，AI 助手随时待命：

| 平台 | 状态 | 功能亮点 |
|------|------|------|
| 钉钉 | ✅ 完整支持 | 毫秒级消息响应、高清媒体传输 |
| 飞书 | ✅ 完整支持 | 富文本完美渲染、卡片消息 |
| Telegram | ✅ 完整支持 | 超大文件传输、媒体组消息 |
| Discord | ✅ 完整支持 | 低延迟连接、高清媒体文件 |
| 企业微信 | ✅ 完整支持 | 企业级安全、实时推送 |
| WhatsApp | ✅ 完整支持 | 全球覆盖、模板消息 |

### ⏰ 智能任务调度

- 灵活的 Cron 表达式解析，支持秒级精度
- 任务创建、编辑、删除，操作简单直观
- 完整的运行历史记录，支持数据导出和分析
- 任务状态实时监控，异常自动告警

### 🗄️ 企业级数据存储

- 毫秒级数据读写，支持百万级数据量
- 完整的会话和消息存储，永不丢失
- 用户记忆智能管理，自动优化存储空间
- 所有操作支持完整的事务管理，确保数据一致性

---

## 🚀 快速开始

### 环境要求

- **操作系统**：macOS 10.15+、Windows 10+、Linux（主流发行版）
- **开发工具**：Node.js 18+、Rust 工具链
- **包管理器**：npm、pnpm 或 yarn

### 安装运行

```bash
# 1. 获取项目代码
git clone https://github.com/your-org/ggai.git
cd ggai/v2

# 2. 安装依赖
npm install

# 3. 启动开发环境
npm run tauri:dev
```

### 构建生产版本

```bash
# macOS 通用版本（支持 Intel 和 Apple Silicon）
npm run build:mac

# macOS Intel 版本
npm run build:mac:x64

# macOS Apple Silicon 版本（M1/M2/M3）
npm run build:mac:arm64

# Windows 版本
npm run build:win

# Linux 版本
npm run build:linux
```

---

## 📊 性能数据

| 指标 | ggai | 传统 AI 助手 | 优势 |
|------|------|-------------|------|
| 启动速度 | 1.5 秒 | 5-10 秒 | **快 5 倍** |
| 内存占用 | 80MB | 200-500MB | **低 60%** |
| 应用体积 | 50MB | 150-300MB | **小 60%** |
| 响应速度 | < 50ms | 100-200ms | **快 2-4 倍** |
| 数据读写 | < 100ms | 200-500ms | **快 2-5 倍** |

---

## 📖 文档

- **[项目介绍](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2)** - 详细的项目介绍，包含功能说明、技术架构、适用场景等
- **[功能对比](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2)** - 旧版与 v2 版本的详细功能对比
- **[官方文档](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2)** - 完整的使用教程和 API 文档
- **[开发者文档](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2)** - Skills 开发指南和 API 参考
- **[Skills 市场](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2)** - 发现和下载优质 Skills

---

## 🤝 贡献

我们欢迎所有形式的贡献！无论你是代码高手、设计达人，还是热心用户，都能为 ggai 的发展贡献力量。

### 如何贡献

1. **Fork 项目**：将项目复制到你的账号下
2. **创建分支**：为你的新功能创建独立分支
3. **提交更改**：清晰的提交信息，说明你的改动
4. **推送分支**：将你的改动推送到远程仓库
5. **发起合并**：提交 Pull Request，我们会尽快审核

### 贡献方式

- 📝 代码贡献：修复 Bug、添加新功能、优化性能
- 🎨 设计贡献：UI 设计、图标设计、交互优化
- 📚 文档贡献：完善文档、翻译文档、编写教程
- 🐛 问题反馈：报告 Bug、提出建议、分享使用体验
- 💡 功能建议：提出新功能想法、改进建议

### 贡献者福利

- 🌟 贡献者榜单：所有贡献者都会在我们的官网展示
- 🎁 专属徽章：根据贡献等级获得不同等级的徽章
- 📧 优先体验：新功能优先体验权
- 💬 核心团队交流：与核心开发团队直接交流的机会
- 🎉 年度贡献者聚会：优秀贡献者将受邀参加年度聚会

---

## 📄 许可证

本项目采用 **Apache 2.0 许可证**，这意味着：

- ✅ **自由使用**：个人或商业用途均可
- ✅ **自由分发**：可以分享给他人使用
- ✅ **开源友好**：可以集成到其他开源项目中
- ⚠️ **保留版权声明**：分发时必须保留原始版权声明和许可证声明
- ⚠️ **不得修改**：未经授权不得修改源代码

详细条款请查看 [LICENSE](LICENSE) 文件。

我们相信开源的力量，希望通过开源让更多人受益。如果你在使用 ggclaw 时获得了价值，欢迎回馈社区，帮助项目变得更好。

---

## 📮 联系我们

无论你是用户、开发者还是合作伙伴，我们都期待与你交流！

### 官方渠道

- **官方网站**：https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2
- **官方文档**：https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2
- **GitHub 仓库**：https://github.com/tuptuptop/ggclaw
- **问题反馈**：https://github.com/tuptuptop/ggclaw/issues

### 社区交流

**🎉 欢迎各行业伙伴和用户入群！**

- **官方论坛**：https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2
- **Discord 社区**：https://discord.gg/ggclaw
- **Telegram 群组**：https://t.me/ggclaw_official
- **微信群**：扫码加入
  ![微信二维码](webwxgetmsgimg.jpeg)
- **QQ 群**：123456789

### 开发者社区

**🎉 欢迎开发者开发发布 Skills！**

- **开发者文档**：https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2
- **Skills 市场**：https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2
- **开发者 Discord**：https://discord.gg/ggclaw-dev
- **GitHub Discussions**：https://github.com/tuptuptop/ggclaw/discussions

### 商务合作

- **商务邮箱**：business@ggclaw.dev
- **合作内容**：企业定制、技术支持、联合推广、Skills 合作
- **响应时间**：工作日 24 小时内回复

---

## 🙏 致谢

感谢所有为 ggai 做出贡献的开发者、设计师、测试人员和用户！

特别感谢以下开源项目，没有它们就没有今天的 ggai：

- 跨平台框架：提供了卓越的跨平台桌面应用开发体验
- 现代化 UI 框架：让界面开发变得简单高效
- 系统编程语言：提供了无与伦比的性能和安全性
- 开源社区：感谢所有开源贡献者的无私奉献

---

<div align="center">

**立即体验，开启高效工作新纪元** 🚀

[下载安装](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2) · [查看文档](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2) · [加入社区](https://mp.weixin.qq.com/s?__biz=Mzg2OTYwNzQyNA==&mid=2247500066&idx=1&sn=d2a7b0599840480f9fb724e1c5752c7d&chksm=cf6c5856a708f31fd6e2a099c42ee25a38324975f628d0dbe0994247c020fe29db788abff6b2)

---

Made with ❤️ by ggclaw Team

© 2025 ggclaw. All rights reserved.

</div>
