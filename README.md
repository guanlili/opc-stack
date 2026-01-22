# OPC Stack

面向“超级个体与超级团队”的导航站 / 能力栈。

## 简介

OPC Stack 是一个精心策划的工具集合，旨在帮助个人和团队提升效率、协作能力和知识管理水平。

## 特性

- **个人效能**: 任务管理、时间管理、笔记工具
- **团队协作**: 项目管理、即时通讯、文档协作
- **知识创造**: 思维导图、写作工具、知识库
- **超级工具**: AI 助手、自动化工具、NoCode
- **独立变现**: 支付网关、数字产品销售、会员系统

## 使用方法

### 本地预览

如果你安装了 Node.js，可以直接运行：

```bash
npx serve .
```

然后访问 http://localhost:3000

## 部署指南

由于本项目是纯静态网站（HTML/CSS/JS），你可以轻松将其部署到任何静态托管平台。

### 1. GitHub Pages（推荐）

如果你已经将代码托管在 GitHub 上：

1. 进入项目仓库的 **Settings** 页面。
2. 点击左侧菜单的 **Pages**。
3. 在 **Build and deployment** > **Source** 下，选择 `Deploy from a branch`。
4. 在 **Branch** 选项中，选择 `main` (或 `master`) 分支，文件夹选择 `/ (root)`。
5. 点击 **Save**。等待几分钟，GitHub 会生成一个访问链接。

### 2. Vercel

1. 访问 [Vercel](https://vercel.com/) 并使用 GitHub 账号登录。
2. 点击 **Add New...** > **Project**。
3. 导入你的 `opc-stack` 仓库。
4. 框架预设（Framework Preset）选择 `Other`。
5. 点击 **Deploy**。

### 3. Netlify

1. 访问 [Netlify](https://www.netlify.com/) 并登录。
2. 点击 **Add new site** > **Import an existing project**。
3. 连接 GitHub 并选择你的仓库。
4. 保持默认构建设置（Build settings），直接点击 **Deploy site**。

## 贡献

欢迎提交 PR 或 Issue 来丰富这个能力栈。
