# 🖼️ 图片转Base64徽章生成器

一个功能强大、现代美观的静态网页工具，专门用于将图片转换为Base64编码，并生成自定义的徽章（Badge）。完美支持Shields.io和Badgen.net两大徽章服务平台，为你的项目文档增色添彩。

[![GitHub stars](https://img.shields.io/github/stars/Smartuil/Chinese-ICP-Badge?style=social)](https://github.com/Smartuil/Chinese-ICP-Badge/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Smartuil/Chinese-ICP-Badge?style=social)](https://github.com/Smartuil/Chinese-ICP-Badge/network)
[![GitHub issues](https://img.shields.io/github/issues/Smartuil/Chinese-ICP-Badge)](https://github.com/Smartuil/Chinese-ICP-Badge/issues)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Live Demo](https://img.shields.io/badge/Demo-Online-brightgreen)](https://Smartuil.github.io/Chinese-ICP-Badge/)

## ✨ 功能特性

### 🎯 核心功能
- 📷 **智能图片上传**: 支持点击选择和拖拽上传，兼容多种图片格式
- 🔄 **实时Base64转换**: 高效的图片编码转换，支持大文件处理
- 🎨 **完全自定义徽章**: 文字内容、颜色方案、图标样式随心定制
- 🛡️ **双平台支持**: 全面兼容Shields.io和Badgen.net服务
- 📋 **便捷复制功能**: 一键复制Base64编码和Markdown代码
- 🎯 **即时预览**: 所见即所得的徽章效果预览

### 🚀 高级特性
- 📱 **完美响应式**: 自适应各种屏幕尺寸，移动端体验优秀
- 🎭 **丰富图标库**: 内置70+预设图标，涵盖开发、社交、云服务等分类
- 🔗 **URL图片支持**: 支持使用在线图片作为徽章图标
- 🎨 **颜色选择器**: 直观的颜色选择和HEX值输入
- 📊 **图标缩放**: 灵活的图标大小调整选项
- ⚡ **零配置部署**: 开箱即用，无需复杂配置

## 🌐 在线体验

👉 **立即体验**: [https://Smartuil.github.io/Chinese-ICP-Badge/](https://Smartuil.github.io/Chinese-ICP-Badge/)

无需下载或安装，直接在浏览器中使用完整功能！

## 📦 快速开始

### 方式一：直接使用（推荐）
访问在线版本，无需任何安装步骤

### 方式二：本地部署

1. **克隆项目**
```bash
git clone https://github.com/Smartuil/Chinese-ICP-Badge.git
cd Chinese-ICP-Badge
```

2. **启动本地服务器**
```bash
# 使用Python（推荐）
python -m http.server 8000

# 或使用Node.js
npx serve .

# 或使用PHP
php -S localhost:8000
```

3. **访问应用**
打开浏览器访问 `http://localhost:8000`

### 方式三：GitHub Pages部署
1. Fork本项目到你的GitHub账户
2. 在仓库设置中启用GitHub Pages
3. 选择`main`分支作为源
4. 访问 `https://你的用户名.github.io/Chinese-ICP-Badge/`

## 📖 详细使用指南

### 📷 图片上传步骤

1. **选择上传方式**
   - 🖱️ **点击上传**: 点击上传区域选择本地图片
   - 🎯 **拖拽上传**: 直接拖拽图片文件到上传区域

2. **支持的图片格式**
   - PNG（推荐，支持透明背景）
   - JPG/JPEG（适合照片）
   - GIF（支持动画）
   - SVG（矢量图形）

3. **图片处理**
   - 自动转换为Base64编码
   - 实时显示图片预览
   - 支持移除和重新上传

### 🎨 Shields.io 徽章配置

| 参数 | 说明 | 示例 |
|------|------|------|
| 徽章标题 | 左侧显示的文字 | "ICP备案" |
| 徽章内容 | 右侧显示的文字 | "京ICP备12345678号" |
| 徽章颜色 | 背景颜色 | "#0066cc" |
| 预设Logo | 内置图标选择 | "github", "twitter" 等 |

### 🎯 Badgen.net 徽章配置

| 参数 | 说明 | 选项 |
|------|------|------|
| 徽章标题 | 左侧文字 | 自定义文本 |
| 徽章内容 | 右侧文字 | 自定义文本 |
| 徽章颜色 | 背景颜色 | 颜色选择器 |
| 图标来源 | 图标类型 | 预设图标 / 图片URL |
| 图标缩放 | 图标大小 | 小/标准/大/特大 |

### 📋 复制功能

- **Base64编码**: 可用于其他项目的图标嵌入
- **Markdown代码**: 直接粘贴到README.md文件中
- **HTML代码**: 可用于网页嵌入

## 🔧 技术架构

### 前端技术栈
- **HTML5**: 语义化标签，无障碍访问
- **Tailwind CSS 2.2**: 原子化CSS框架，快速样式开发
- **Vanilla JavaScript**: 纯JS实现，无框架依赖
- **CSS3动画**: 流畅的过渡效果和微交互

### 核心特性
- 🌐 **CDN优化**: 使用可靠的CDN加速资源加载
- 🎨 **现代UI**: 渐变背景、毛玻璃效果、悬浮动画
- 📱 **PWA就绪**: 支持离线使用和安装到主屏幕
- 🔒 **安全可靠**: 所有处理都在本地完成，无数据上传风险

## 📚 API参考

### Shields.io URL格式
```
https://img.shields.io/badge/{LABEL}-{MESSAGE}-{COLOR}?logo={LOGO}
```

### Badgen.net URL格式
```
https://badgen.net/badge/{SUBJECT}/{STATUS}/{COLOR}?icon={ICON}&scale={SCALE}
```

### 参数说明
- `{LABEL}/{SUBJECT}`: 徽章标题
- `{MESSAGE}/{STATUS}`: 徽章内容  
- `{COLOR}`: 颜色代码（支持HEX和命名颜色）
- `{LOGO}/{ICON}`: 图标名称或URL
- `{SCALE}`: 图标缩放比例

## 🎯 使用场景

### 🏢 企业应用
- ICP备案号展示
- 安全合规标识
- 企业认证徽章

### 👨‍💻 开发项目
- 构建状态徽章
- 版本信息展示
- 依赖管理标识

### 📚 文档美化
- README装饰
- 技术栈展示
- 项目状态标识

### 🌐 个人品牌
- 社交媒体链接
- 技能认证徽章
- 成就展示

## 🤝 贡献指南

我们欢迎所有形式的贡献！

### 🐛 报告问题
- 使用GitHub Issues报告bug
- 提供详细的重现步骤
- 包含浏览器和系统信息

### 💡 功能建议
- 在Issues中描述新功能需求
- 说明使用场景和预期效果
- 欢迎提供设计草图或原型

### 🔧 代码贡献
1. Fork本项目
2. 创建功能分支: `git checkout -b feature/amazing-feature`
3. 提交更改: `git commit -m 'Add amazing feature'`
4. 推送分支: `git push origin feature/amazing-feature`
5. 提交Pull Request

### 📝 开发规范
- 保持代码简洁易读
- 遵循现有的代码风格
- 添加必要的注释
- 测试所有修改功能

## 📄 许可证

本项目采用 [MIT License](LICENSE) 开源协议。

## 🙏 致谢

感谢以下开源项目和服务：

- [Shields.io](https://shields.io/) - 优秀的徽章生成服务
- [Badgen.net](https://badgen.net/) - 现代化的徽章生成器
- [Tailwind CSS](https://tailwindcss.com/) - 实用优先的CSS框架
- [GitHub Pages](https://pages.github.com/) - 免费的静态网站托管

## 📞 联系方式

- 📧 **邮箱**: [your-email@example.com]
- 🐛 **Issues**: [GitHub Issues](https://github.com/Smartuil/Chinese-ICP-Badge/issues)
- 💬 **讨论**: [GitHub Discussions](https://github.com/Smartuil/Chinese-ICP-Badge/discussions)

---

<div align="center">

**⭐ 如果这个项目对你有帮助，请给一个Star支持一下！**

Made with ❤️ by [Smartuil](https://github.com/Smartuil)

</div>

## 🎨 示例展示

### 基础徽章
![示例1](https://img.shields.io/badge/ICP备案-京ICP备12345678号-blue)
![示例2](https://badgen.net/badge/构建/通过/green)

### 带图标徽章
![示例3](https://img.shields.io/badge/GitHub-开源项目-informational?logo=github)
![示例4](https://badgen.net/badge/技术栈/React/blue?icon=react&scale=1.2)

### 自定义颜色徽章
![示例5](https://img.shields.io/badge/状态-进行中-FF6B6B)
![示例6](https://badgen.net/badge/版本/v2.0.0/9B59B6)

> 💡 **提示**: 所有徽章都可以通过本工具轻松生成和自定义！