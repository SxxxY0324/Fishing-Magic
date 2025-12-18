# 透明浏览器 (Transparent Browser)

一个基于 Electron 的透明桌面浏览器，专为抖音和B站设计。

## 功能特性

- **透明度调节** - 窗口透明度可在 20%-100% 之间调节
- **音量控制** - 独立控制视频音量，支持一键静音
- **双击静音最小化** - 双击顶部空白区域快速静音并最小化
- **快捷按钮** - ⏬ 按钮一键静音并最小化
- **网站切换** - 一键切换抖音/B站
- **无边框窗口** - 简洁的无边框透明设计
- **可调整大小** - 拖拽窗口四角调整大小

## 默认设置

- 透明度：50%
- 音量：0%（静音）

## 安装

```bash
# 克隆仓库
git clone https://github.com/SxxxY0324/Fishing-Magic.git
cd Fishing-Magic

# 安装依赖
npm install

# 运行
npm start
```

## 打包

```bash
# Windows
npm run build:win

# macOS
npm run build:mac

# Linux
npm run build:linux
```

打包后的文件在 `dist` 目录下。

## 使用说明

| 操作 | 功能 |
|------|------|
| 拖拽空白区域 | 移动窗口 |
| 双击空白区域 | 静音并最小化 |
| 点击 ⏬ 按钮 | 静音并最小化 |
| 点击音量图标 | 切换静音/恢复音量 |
| 拖拽窗口四角 | 调整窗口大小 |

## 技术栈

- Electron 28
- HTML/CSS/JavaScript

## License

MIT
