# 🚀 Prompt优化器

AI智能提示词优化工具 - 使用 GitHub Models API 优化您的 Prompt

## ✨ 功能特性

- 🤖 **AI智能优化** - 使用 GPT-4o 模型优化您的 Prompt
- 📝 **多种模板** - 提供代码、写作、分析、创意等快速模板
- 📋 **历史记录** - 自动保存优化历史到本地存储
- 📱 **响应式设计** - 完美支持桌面端和移动端
- 🔒 **隐私保护** - 本地存储，数据不会上传到服务器

## 🌐 在线访问

### 方式一：GitHub Pages（推荐）
**访问地址**: https://ttjacky2023-spec.github.io/prompt-optimizer/

### 方式二：Vercel部署
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ttjacky2023-spec/prompt-optimizer)

点击上方按钮，即可一键部署到您的 Vercel 账户

## 🛠️ 本地使用

1. 克隆仓库
```bash
git clone https://github.com/ttjacky2023-spec/prompt-optimizer.git
```

2. 进入项目目录
```bash
cd prompt-optimizer
```

3. 使用任意静态服务器运行
```bash
npx serve .
```

4. 在浏览器中访问 `http://localhost:3000`

## 🔑 配置 GitHub Token

首次使用时需要配置 GitHub Personal Access Token：

1. 访问 https://github.com/settings/tokens
2. 点击 "Generate new token (classic)"
3. 勾选以下权限：
   - `read:packages` - 读取包权限
4. 生成并复制 token
5. 在应用首次启动时粘贴 token

Token 将保存在浏览器本地存储中，不会上传到任何服务器。

## 📝 使用说明

1. 在输入框中输入您需要优化的原始 Prompt
2. 或点击快速模板按钮插入预设模板
3. 点击"✨ 优化 Prompt"按钮
4. 等待 AI 返回优化结果
5. 使用"复制"按钮复制优化后的 Prompt

## 🔧 技术栈

- HTML5 + CSS3
- Tailwind CSS (CDN)
- Vanilla JavaScript
- GitHub Models API

## 📄 许可证

MIT License
