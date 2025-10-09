# AtelierX - AI-Powered Fashion Design Platform

## 项目简介

AtelierX是一个基于n8n的AI驱动时尚设计平台，集成了灵感收集、打版分析、智能问答和供货商管理等功能。

## 功能特性

- 🎨 **灵感收集分析** - AI驱动的设计灵感收集和分析
- 📐 **打版分析** - 智能打版风险评估和分析
- 💬 **智能问答** - 基于AI的时尚设计问答系统
- 🏪 **供货商管理** - 供货商查询和地图展示
- 📱 **响应式设计** - 适配各种设备尺寸

## 快速开始

### 本地测试

1. 下载项目到本地
2. 直接在浏览器中打开 `n8n的前端/主页.html`
3. 或者使用本地服务器：
   ```bash
   # 使用Python启动本地服务器
   python -m http.server 8000
   # 然后访问 http://localhost:8000/n8n的前端/主页.html
   ```

### 在线测试

项目已部署到以下平台，可以直接在线测试：

- **GitHub Pages**: https://yiwen064.github.io/AtelierX/
- **Netlify**: https://atelierx-demo.netlify.app/

## 项目结构

```
AtelierX/
├── n8n的前端/           # 前端页面
│   ├── 主页.html        # 主页面
│   ├── 个人.html        # 个人中心
│   ├── 供货商.html      # 供货商页面
│   ├── 打版分析.html    # 打版分析页面
│   ├── 灵感来源.html    # 灵感来源页面
│   └── 设计图/          # 设计资源
├── md/                  # 项目文档
└── README.md           # 项目说明
```

## 技术栈

- HTML5 + CSS3 + JavaScript
- n8n 工作流引擎
- 响应式设计
- AI集成

## 测试说明

1. **功能测试**：点击各个页面链接，测试页面跳转
2. **响应式测试**：调整浏览器窗口大小，测试移动端适配
3. **交互测试**：测试表单提交、按钮点击等交互功能

## 联系方式

- GitHub: [yiwen064](https://github.com/yiwen064)
- 项目地址: https://github.com/yiwen064/AtelierX

## 许可证

MIT License
