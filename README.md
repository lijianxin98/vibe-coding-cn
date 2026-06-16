# VibeCoding-cn

**VibeCoding 中文版** - AI 编程学习与结对编程平台

> 让每一个想法，都能在氛围感中被 AI 帮助实现。
> Vibe Coding 不是简单的提示词，而是一种让开发者与 AI 自然对话、松张创造的新工作流程。

---

## 🌟 项目概览

VibeCoding 是一个面向中文开发者的 **AI 辅助编程学习平台**，致力于打造高品质、高氛围感的交互式 AI 编程教育体验。

通过与 AI 的“氛围对话”式结对编程（Vibe Coding），帮助学习者从零基础或进阶开发者，快速将想法变为可运行的代码项目。

平台提供交互式编辑器、实时 AI 流式响应、模块化任务拆解、代码执行环境（WebContainer / Pyodide）等核心功能，让学习和开发变得更有趣、更高效、更有“vibe”。

---

## 🚀 核心特性

- **氛围式 AI 结对编程** ：支持自然语言描述需求，AI 帮助规划、代码生成、调试与优化
- **现代前端技术栈** ：Next.js 15 + App Router + TypeScript + Tailwind CSS + shadcn/ui
- **代码编辑与执行** ：Monaco Editor 支持多语言、实时高亮 + WebContainer 和 Pyodide 实现浏览器内运行环境
- **AI 流式体验** ：Vercel AI SDK + Streaming 响应，支持 Grok、Claude、GPT 等多模型路由
- **学习路径与课程** ：模块化学习路径（入门、进阶、项目实战），支持课程审核与“AI 味道”检测
- **隐私与稳定性** ：支持本地代理、多账号管理、隐私保护设置
- **开放与扩展** ：开源核心代码，支持自定义 Agent、Prompt 模板库、多人协作

---

## 📁 项目目录结构（计划）

```
vibe-coding-cn/
├── app/                    # Next.js App Router
│   ├── (main)/             # 主应用路由
│   ├── api/               # API 路由（AI 流式等）
│   └── globals.css
├── components/            # shadcn/ui 组件库
├── lib/                   # 工具库、AI 客户端、Prompt 管理
├── hooks/                 # 自定义 React Hooks
├── public/                # 静态资源
├── docs/                  # 文档、教程、路线图
├── prompts/               # AI Prompt 模板库（核心）
├── .env.example
├── next.config.js
├── package.json
├── tsconfig.json
└── README.md
```

---

## 🛠️ 技术栈

- **Frontend**: Next.js 15 (App Router), React 19, TypeScript, Tailwind CSS, shadcn/ui, Lucide Icons
- **Editor**: Monaco Editor (@monaco-editor/react)
- **AI Integration**: Vercel AI SDK, AI SDK for streaming responses
- **Runtime**: WebContainer API (for Node.js projects), Pyodide (Python in browser)
- **Backend/Edge**: Next.js API Routes / Edge Functions, optional tRPC or Server Actions
- **Auth & Data**: NextAuth.js / Clerk 或本地解决方案，Supabase / Drizzle ORM
- **Deployment**: Vercel (recommended), or self-hosted with Docker
- **AI Models**: Grok API, Claude (via proxy), OpenAI, local models via Ollama / OpenClaw

---

## 📋 路线图 (Roadmap)

### Phase 1: MVP 基础版 (2026 Q2-Q3)
- [ ] 基础页面布局与导航
- [ ] Monaco Editor 集成与基本代码高亮
- [ ] AI 聊天界面 + Streaming 响应 (Vercel AI SDK)
- [ ] 简单项目创建模板（Hello World、Todo App）
- [ ] WebContainer 基础集成（浏览器内运行 JS/TS）

### Phase 2: 学习体验强化
- [ ] 模块化学习路径（入门 / 进阶 / 实战）
- [ ] Prompt 模板库与可视化编辑
- [ ] 代码执行器与调试工具
- [ ] 用户进度追踪与成就系统
- [ ] 多模型支持与路由选择

### Phase 3: 高级功能
- [ ] Pyodide Python 执行环境
- [ ] 多人协作与实时同步编辑
- [ ] 课程审核与 AI 内容检测（“AI 味道”评估）
- [ ] 本地 OpenClaw Agent 集成
- [ ] 移动端适配与 PWA

---

## 🔧 开始使用

```bash
# 克隆仓库
 git clone https://github.com/lijianxin98/vibe-coding-cn.git
 cd vibe-coding-cn

# 安装依赖
 pnpm install   # 或 npm install / yarn

# 启动开发服务器
 pnpm dev
```

打开 http://localhost:3000 即可体验。

> **注意**：目前为初始化阶段，请参看 `docs/` 目录下的开发指南。

---

## 🤝 贡献与参与

欢迎提交 PR、Issue 或反馈！

- 提交前请阅读 `CONTRIBUTING.md` （将在后续添加）
- 关于 Prompt 工程、AI 工作流程的讨论请在 Discussions 中进行
- 本项目遵循 MIT 许可证

---

## 📊 相关链接

- 官方网站：将于 vibe coding.cn 部署
- 相关教程：参考 [vibe-coding-cn 相关资源](https://github.com/tradecatlabs/vibe-coding-cn) 和 [2025Emma/vibe-coding-cn](https://github.com/2025Emma/vibe-coding-cn)
- 技术社区： Vibe Coding 与 AI 编程教育

---

**Made with ❤️ by the VibeCoding Team | 中文 AI 编程教育的未来**