# 🦋 Hexo Butterfly Theme Blog

[![Hexo Version](https://img.shields.io/badge/Hexo-6.3%2B-blue?logo=hexo)](https://hexo.io/)
[![Theme Version](https://img.shields.io/badge/Butterfly-4.9%2B-pink)](https://butterfly.js.org/)
[![Node.js](https://img.shields.io/badge/Node.js-14%2B-green?logo=node.js)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

&gt; 基于 Hexo 框架与 Butterfly 主题构建的个人技术博客，专注于前端开发、工程化实践与技术沉淀。

---

## 📋 目录

- [项目简介](#-项目简介)
- [在线预览](#-在线预览)
- [功能特性](#-功能特性)
- [技术栈](#-技术栈)
- [快速开始](#-快速开始)
- [项目结构](#-项目结构)
- [配置说明](#-配置说明)
- [写作规范](#-写作规范)
- [部署指南](#-部署指南)
- [更新日志](#-更新日志)
- [致谢](#-致谢)

---

## 🎯 项目简介

本项目是一个现代化的静态博客系统，采用 **Hexo** 作为博客框架，**Butterfly** 作为主题，旨在打造：

- ✨ **极致阅读体验**：暗黑模式、流畅动画、响应式设计
- 🚀 **高性能访问**：静态生成、图片懒加载、CDN 加速
- 🛠️ **开发者友好**：代码高亮、目录导航、全文搜索
- 📱 **多端适配**：完美支持桌面端、平板与移动设备

**核心优势：**
- 零服务端依赖，部署简单（支持 Vercel/Netlify/GitHub Pages）
- Markdown 原生支持，专注内容创作
- 丰富的插件生态，功能扩展灵活
- SEO 友好，自动生成 Sitemap 与 RSS

---

## 🌐 在线预览

| 平台 | 地址 | 状态 |
|------|------|------|
| **主站** | https://your-blog-domain.com | ![Online](https://img.shields.io/badge/Status-Online-brightgreen) |
| **备用** | https://your-blog.vercel.app | ![Online](https://img.shields.io/badge/Status-Online-brightgreen) |

**截图展示：**

![首页预览](https://your-cdn-link.com/homepage-screenshot.png)
*首页 - 文章卡片流与侧边栏*

![文章页预览](https://your-cdn-link.com/post-screenshot.png)
*文章详情 - 代码高亮与目录导航*

![暗黑模式](https://your-cdn-link.com/darkmode-screenshot.png)
*暗黑模式 - 自动切换与手动切换*

---

## ✨ 功能特性

### 基础功能
- [x] **响应式布局**：适配 320px - 4K 全分辨率
- [x] **暗黑模式**：自动跟随系统/手动切换/定时切换
- [x] **PWA 支持**：离线访问、添加到主屏
- [x] **多语言**：简体中文、English 切换

### 内容展示
- [x] **文章系统**：标签、分类、归档、置顶
- [x] **代码高亮**：Mac 风格代码框、行号显示、代码复制
- [x] **数学公式**：KaTeX 渲染数学表达式
- [x] **图表支持**：Mermaid 流程图、Chart.js 数据可视化
- [x] **多媒体**：图片懒加载、视频嵌入、音乐播放器

### 交互体验
- [x] **即时搜索**：Algolia/Local Search 全文检索
- [x] **评论系统**：Twikoo/Valine/Gitalk 多平台支持
- [x] **文章分享**：一键复制链接、生成分享图
- [x] **阅读统计**：LeanCloud/不蒜子浏览量统计
- [x] **版权保护**：文章底部自动添加版权信息

### 性能优化
- [x] **懒加载**：图片、评论、第三方脚本延迟加载
- [x] **预加载**：Instant.page/Pjax 快速导航
- [x] **CDN 加速**：静态资源托管至 jsDelivr/UNPKG
- [x] **SEO 优化**：自动生成 Schema.org 结构化数据

### 扩展功能
- [x] **友链页面**：双向链接、头像懒加载
- [x] **关于页面**：时间线、技能标签、项目展示
- [x] **404 页面**：个性化设计、返回首页引导
- [x] **站点统计**：百度统计/Google Analytics

---

## 🛠️ 技术栈

| 类别 | 技术 | 版本 | 说明 |
|------|------|------|------|
| **博客引擎** | Hexo | 6.3.0+ | 快速、简洁且高效的博客框架 |
| **主题** | Butterfly | 4.9.0+ | 美观且功能丰富的 Hexo 主题 |
| **运行环境** | Node.js | 14.x+ | JavaScript 运行时 |
| **包管理** | npm/yarn/pnpm | - | 依赖管理工具 |
| **部署平台** | Vercel | - | 边缘网络部署与托管 |
| **图床** | GitHub + jsDelivr | - | 免费 CDN 图片加速 |
| **评论服务** | Twikoo | 1.6.0+ | 基于腾讯云开发的评论系统 |
| **搜索服务** | Algolia | - | 高性能全文搜索引擎 |

---

## 🚀 快速开始

### 环境准备

确保本地已安装：
- [Node.js](https://nodejs.org/) 14.0 或更高版本
- [Git](https://git-scm.com/) 版本控制工具
- [Hexo CLI](https://hexo.io/docs/#Install-Hexo) 命令行工具

```bash
# 安装 Hexo CLI（全局）
npm install -g hexo-cli

# 验证安装
hexo --version
