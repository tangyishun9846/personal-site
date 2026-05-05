# Personal Site · 唐翊舜 Tang Yishun

> **AI Engineer · Generative AI Oriented**
>
> 技术 × 业务 双轮驱动 — 从 Prompt 到 Agent，把复杂痛点工程化。

![preview](og-image.png)

[English](#english) · [日本語](#日本語)

---

## 🇨🇳 中文

一个苹果官网风格的个人主页，记录我作为 AI 工程师的成长历程、核心能力与代表作品。

🌐 **在线预览：** _部署后填入你的 Netlify / GitHub Pages 链接_

### ✨ 特点

- 🎨 **苹果官网风格** — 极简留白、渐进动画、SF Pro 字体
- 🌍 **三语切换** — 中文 · English · 日本語（自动按浏览器语言加载）
- 💬 **AI 数字分身** — 右下角悬浮聊天框，接入 Coze + 个人读书知识库
- 📱 **完全响应式** — 桌面 / 平板 / 手机自适应
- 🎬 **滚动微动效** — Intersection Observer + 数字计数动画
- 🔗 **社交分享优化** — Open Graph 卡片，链接发到任何地方都有预览图
- 📄 **简历一键导出 PDF** — 浏览器打印另存即可
- ⚡ **零依赖** — 纯 HTML / CSS / JS，单文件部署，加载飞快

### 🏗 内容结构

| 区块 | 说明 |
|---|---|
| Hero | 头像 + 姓名 + 一句话定位 |
| About | 跨界经历自述 + 关键数据卡片 |
| Skills | 6 项 AI 核心能力（LLM 选型 / Prompt / RAG / Agent / Python / 评估） |
| Projects | 3 个代表作品，每个配设计感 SVG 可视化 + 数据指标 |
| Journey | 5 阶段成长时间轴（科班 → 创业 → 跨境 → 大厂验证 → AI 工程） |
| Contact | 邮件 / 电话 / 简历 PDF |

### 🛠 技术栈

- **前端**：原生 HTML5 + CSS3 + Vanilla JS，无框架依赖
- **可视化**：手写 SVG 项目示意图
- **国际化**：自建轻量 i18n 系统，单 HTML 内嵌词典
- **AI 助手**：Coze Web SDK（接入个人读书知识库做 RAG 检索）
- **部署**：Netlify / GitHub Pages / Vercel 任选

### 🚀 本地运行

无需构建，浏览器直接打开即可：

```bash
open index.html
```

或使用任意静态服务器：

```bash
python3 -m http.server 8000
# 访问 http://localhost:8000
```

### 📁 文件结构

```
.
├── index.html       # 主页面（含所有 CSS/JS/i18n）
├── photo.jpg        # 头像照片
├── og-image.png     # 社交分享卡片图（1200×630）
├── README.md        # 本文件
└── .gitignore
```

### 🚢 部署到 Netlify

1. Fork 本仓库
2. 登录 [Netlify](https://app.netlify.com/) → New site from Git
3. 选择此仓库，构建设置全部留空，Publish directory 填 `/`
4. 部署完成，会得到 `xxx.netlify.app` 域名

---

## English

A personal site in Apple-inspired style, showcasing my journey, capabilities and selected works as an AI Engineer.

### Highlights

- Apple-style minimal aesthetic
- Trilingual (中 / EN / 日), browser-locale aware
- AI chat assistant powered by Coze + personal reading knowledge base
- Fully responsive, scroll-triggered animations, count-up stats
- Open Graph share card, one-click resume PDF
- Zero framework dependency — single HTML file

### Tech Stack

Vanilla HTML/CSS/JS · SVG illustrations · Custom i18n · Coze Web SDK · Static hosting

### Run Locally

```bash
open index.html
# or
python3 -m http.server 8000
```

---

## 日本語

Apple 公式サイト風のパーソナルサイト。AI エンジニアとしての歩み、コアスキル、代表作品を紹介します。

### 特徴

- ミニマルなデザイン、なめらかなアニメーション
- 多言語対応（中 / EN / 日）— ブラウザ言語で自動切替
- Coze + 読書ナレッジベース駆動の AI チャットアシスタント
- 完全レスポンシブ、スクロール起点のアニメーション
- OG カード、ワンクリック履歴書 PDF 出力
- フレームワーク非依存、シングルファイル

---

## 📬 Contact

- ✉️ **Email**: [tangyishun9846@gmail.com](mailto:tangyishun9846@gmail.com)
- 📱 **Phone**: 155 4138 3107

## 📜 License

© 2026 唐翊舜 · Tang Yishun. All rights reserved.

---

<sub>Built with care · Polished with iteration · Powered by curiosity</sub>
