# 🎨 Emoji2Pixel

将表情符号和图片转换为精美的像素艺术。这是一个功能强大的网页端转换工具，可以创建惊艳的动画效果，自定义各种细节，并将作品导出为图片或GIF动画。

![Emoji2Pixel Badge](https://img.shields.io/badge/Emoji2Pixel-v1.0-brightgreen) ![License](https://img.shields.io/badge/license-MIT-blue) ![Languages](https://img.shields.io/badge/languages-8-orange)

## ✨ 功能特性

### 🖼️ **多来源输入**
- **表情符号支持**：直接输入emoji或从全面的表情库中浏览选择
- **图片导入**：上传任意图片文件进行像素化
- **自动拟合模式**：自动调整emoji缩放比例以完美适配画布
- **搜索与筛选**：快速emoji搜索，支持分类导航

### 🎬 **动画系统**
- **关键帧动画**：创建包含多个关键帧的流畅动画
- **过渡插值**：自动生成关键帧之间的过渡帧
- **播放控制**：实时播放、暂停和调整动画速度
- **GIF导出**：将动画导出为GIF动画文件

### 🎛️ **高级变换控制**
- **缩放**：调整作品大小，范围0%-200%
- **位置**：精细调整X/Y偏移，实现完美对齐
- **旋转**：任意方向旋转（0-360°）
- **交互式画布**：点击拖动直接操作，按住Shift键旋转

### 🎨 **强大的渲染引擎**
- **双重渲染模式**：
  - **理想模式**：专业像素艺术，支持自定义间隙和边框
  - **裸渲染模式**：纯像素渲染，呈现复古风格
- **灵活画布**：可调整网格大小（8x8至128x128像素）
- **像素样式**：选择方形、圆角或圆形像素
- **色彩量化**：将色板减少至2-256色，营造复古美学
- **锐化滤镜**：增强边缘清晰度，可调节强度

### 🖌️ **编辑工具**
- **背景去除**：智能背景去除，支持容差控制
- **选区工具**：矩形选区，支持填充、擦除、复制和粘贴
- **图层系统**：无损编辑工作流
- **撤销支持**：撤销取色和背景去除操作

### 📏 **专业导出选项**
- **多种单位**：支持毫米、英寸或网格单位工作
- **尺寸预设**：常用显示尺寸的快速预设
- **导出格式**：
  - PNG（支持透明度）
  - GIF（动画或静态）
  - 原始像素数据
- **帧渲染**：用真实世界尺寸可视化物理像素布局

### 🌍 **国际化支持**
内置8种语言翻译：
- 🇨🇳 简体中文
- 🇺🇸 English（英语）
- 🇫🇷 Français（法语）
- 🇩🇪 Deutsch（德语）
- 🇮🇹 Italiano（意大利语）
- 🇯🇵 日本語（日语）
- 🇰🇷 한국어（韩语）
- 🇪🇸 Español（西班牙语）

## 🚀 快速开始

### 在线演示
访问在线演示：[https://thomas-hiddenpeak.github.io/emoji2pixel](https://thomas-hiddenpeak.github.io/emoji2pixel)

### 本地开发

1. **克隆仓库**
   ```bash
   git clone https://github.com/thomas-hiddenpeak/emoji2pixel.git
   cd emoji2pixel
   ```

2. **本地服务**
   
   使用Python：
   ```bash
   python -m http.server 8000
   ```
   
   或使用Node.js：
   ```bash
   npx http-server -p 8000
   ```

3. **浏览器访问**
   ```
   http://localhost:8000
   ```

无需构建过程！这是一个纯静态网页应用。

## 📖 使用指南

### 基本工作流程

1. **输入**：输入emoji或上传图片
2. **变换**：调整缩放、位置和旋转至满意
3. **添加帧**：点击`+`按钮添加到动画中
4. **自定义**：调整渲染设置、像素样式和颜色
5. **导出**：下载为PNG或GIF

### 快捷键

| 快捷键 | 功能 |
|--------|------|
| `空格` | 切换动画播放/暂停 |
| `回车` | 将当前视图添加为关键帧 |
| `Delete` / `退格` | 删除选中的帧 |
| `←` / `→` | 在帧之间导航 |
| `Esc` | 取消选区/取色 |
| `Ctrl/Cmd + C` | 复制选区 |
| `Ctrl/Cmd + V` | 粘贴选区 |

### 专业技巧

- 🎯 在画布上**按住Shift**拖动可以旋转而非移动
- 🔍 使用**色彩量化**（8-64色）实现正宗复古像素艺术
- ⚡ 启用**锐化**（30-50%强度）以增强边缘清晰度
- 🎬 设置**过渡帧数**为5-10以获得流畅动画
- 📐 使用**帧渲染模式**可视化物理LED矩阵布局

## 🛠️ 技术栈

- **纯前端**：HTML5、CSS3、原生JavaScript
- **零依赖**：无需外部库或框架
- **Canvas API**：高性能像素操作
- **GIF.js**：客户端GIF编码
- **响应式设计**：适配桌面和平板设备

## 📁 项目结构

```
emoji2pixel/
├── index.html          # 主HTML结构
├── app.js              # 核心应用逻辑
├── styles.css          # 样式和布局
├── locales/            # 国际化
│   ├── index.json      # 语言清单
│   ├── zh-CN.json      # 中文翻译
│   ├── en-US.json      # 英文翻译
│   └── ...             # 其他语言
├── docs/               # 多语言文档
│   ├── README.zh-CN.md # 中文说明
│   ├── README.en.md    # 英文说明
│   └── ...             # 其他语言说明
└── scripts/            # 构建工具
    └── generate_locales_index.py
```

## 🌐 添加新语言

1. 在`locales/`中创建新的语言文件（例如：`pt-BR.json`）
2. 从现有语言文件复制结构
3. 翻译所有键值对到目标语言
4. 添加带有国旗emoji的`selfName`字段
5. 运行语言索引生成器：
   ```bash
   python scripts/generate_locales_index.py
   ```

新语言会自动出现在语言选择器中！

## 🤝 贡献

欢迎贡献！以下是你可以帮助的方式：

- 🐛 报告bug和问题
- 💡 建议新功能
- 🌍 添加或改进翻译
- 📝 改进文档
- 🎨 提交像素艺术作品展示

### 开发指南

1. Fork此仓库
2. 创建功能分支（`git checkout -b feature/amazing-feature`）
3. 提交你的更改（`git commit -m 'Add amazing feature'`）
4. 推送到分支（`git push origin feature/amazing-feature`）
5. 开启Pull Request

## 📄 许可证

本项目采用MIT许可证 - 详见[LICENSE](../LICENSE)文件。

## 🙏 致谢

- Emoji数据来源于Unicode标准
- 灵感来自经典像素艺术工具和LED矩阵显示
- 用❤️为像素艺术社区打造

## 📮 联系与支持

- **问题反馈**：[GitHub Issues](https://github.com/thomas-hiddenpeak/emoji2pixel/issues)
- **讨论交流**：[GitHub Discussions](https://github.com/thomas-hiddenpeak/emoji2pixel/discussions)

---

<div align="center">

**用🎨和⌨️制作**

如果觉得这个项目有用，请给一个⭐！

[English](README.en.md) | [Français](README.fr.md) | [Deutsch](README.de.md) | [Italiano](README.it.md) | [日本語](README.ja.md) | [한국어](README.ko.md) | [Español](README.es.md)

</div>
