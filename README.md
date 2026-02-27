# 🚀 Prompt优化器

AI智能提示词优化工具 - 支持 Kimi AI 和 GitHub Models API

## ✨ 功能特性

- 🤖 **双AI引擎** - 支持 Kimi AI 和 GitHub Models (GPT-4o)
- 📝 **模板管理** - 创建、编辑、删除自定义Prompt模板
- 🎨 **快速模板** - 内置代码、写作、分析、创意等模板
- 📋 **历史记录** - 自动保存优化历史到本地存储
- 📱 **响应式设计** - 完美支持桌面端和移动端
- 🔒 **隐私保护** - 本地存储，数据不会上传到服务器
- ⚡ **快捷键支持** - Ctrl+Enter 快速优化

## 🌐 在线访问

### GitHub Pages（推荐）
**访问地址**: https://ttjacky2023-spec.github.io/prompt-optimizer/

### Vercel部署
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/ttjacky2023-spec/prompt-optimizer)

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

## 🔑 配置 API Key

### Kimi AI（推荐）
1. 访问 https://platform.moonshot.cn
2. 注册并登录账号
3. 在控制台中创建 API Key
4. 在应用设置中粘贴 Kimi API Key

### GitHub Models（备选）
1. 访问 https://github.com/settings/tokens
2. 点击 "Generate new token (classic)"
3. 勾选以下权限：
   - `read:packages` - 读取包权限
4. 生成并复制 token
5. 在应用设置中粘贴 GitHub Token

## 📝 使用说明

### 基础使用
1. 在输入框中输入您需要优化的原始 Prompt
2. 或点击快速模板按钮插入预设模板
3. 点击"✨ 开始优化"按钮
4. 等待 AI 返回优化结果
5. 使用"复制"按钮复制优化后的 Prompt

### 模板管理
1. 点击"管理模板"按钮打开模板管理器
2. **添加模板**：填写名称、内容、标签颜色后点击添加
3. **编辑模板**：点击模板旁边的编辑按钮
4. **删除模板**：点击模板旁边的删除按钮
5. **使用模板**：点击任意模板即可插入到输入框

### API切换
1. 点击"配置"按钮打开API设置
2. 选择 Kimi AI 或 GitHub 作为API提供商
3. 系统会自动使用对应的API进行优化

### 快捷键
- `Ctrl + Enter` - 快速开始优化
- `Esc` - 关闭弹窗

## 🎨 模板标签颜色

- `blue` - 蓝色（代码相关）
- `green` - 绿色（写作相关）
- `yellow` - 黄色（分析相关）
- `pink` - 粉色（创意相关）
- `purple` - 紫色（其他）

## 🔧 技术栈

- HTML5 + CSS3
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Kimi API (Moonshot AI)
- GitHub Models API

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📧 联系方式

如有问题或建议，欢迎通过 GitHub Issues 联系。
