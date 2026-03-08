# 📅 自律会办公室排班系统 (Office Scheduling System)

![Version](https://img.shields.io/badge/version-2.1-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

一个基于 HTML5 和 JavaScript 的轻量级、响应式办公室排班管理工具。专为高校学生组织设计，旨在解决繁琐的课表收集与人工排班问题。

## ✨ 项目特性

- **极致视觉体验**：采用玻璃拟态（Glassmorphism）设计风格，支持侧边栏丝滑收缩与动态居中布局。
- **本地化隐私保护**：遵循数据私有化原则，所有排班数据均存储在浏览器的 `localStorage` 中，不上传服务器，保护同学们的隐私。
- **高效处理能力**：集成 **SheetJS** 库，支持 Excel 课表的一键导入与导出。
- **智能化排班**：内置自动化排班算法，告别手动对比课表的低效工作。
- **纯前端架构**：无需配置服务器环境，双击 `index.html` 或通过 GitHub Pages 即可部署使用。

## 🛠️ 技术栈

- **前端核心**：HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+)
- **外部库**：[SheetJS (XLSX)](https://sheetjs.com/) - 处理 Excel 逻辑
- **设计风格**：现代简约，适配高刷新率显示器 (如 2K 240Hz)

## 🚀 快速开始

1. **克隆项目**
   ```bash
   git clone [https://github.com/gumhgf/gumhgf.github.io.git](https://github.com/gumhgf/gumhgf.github.io.git)
本地运行
直接用浏览器打开 index.html 即可。

部署
上传至 GitHub 仓库并开启 GitHub Pages 服务。

📸 界面预览
此处可以放入你的系统截图，展示你辛苦调试的丝滑侧边栏和半透明卡片效果。

🔧 开发记录 (v21 更新日志)
Layout 优化：重构了侧边栏与主体的位移算法，解决了 Flex 布局下居中动画不同步的问题。

组件本地化：将 xlsx.full.min.js 等核心库本地化，提升加载速度并增强断网可用性。

交互升级：优化了收起按钮的“边缘锚定”逻辑，确保侧边栏完全隐藏时依然可以轻松找回。

🤝 贡献与反馈
如果你有更好的算法建议（例如更复杂的权重排班算法），欢迎提交 Pull Request 或 Issue。
