# Cover Make

基于 Web 的封面图片生成工具，支持多平台尺寸、丰富背景效果、自定义文字与图标。

![CoverMake](https://img.eucalyptus.cc/images/covermake.png)

地址：https://cover.eucalyptus.cc

## ✨ 功能特性

- **背景**：渐变（线性/径向/圆锥）、纯色、自定义图片（可调模糊/暗化）、网格渐变、噪点纹理、随机配色
- **文字**：主标题/副标题/作者名三层独立控制，23 款中文字体，画布拖拽定位，支持多个自定义文字
- **图标**：粘贴 SVG 代码或上传文件，纯色/毛玻璃容器，圆角/圆形/菱形形状，可配投影与边框，画布拖拽
- **平台预设**：内置 6 种尺寸（博客封面、公众号、小红书、视频封面、PPT、抖音竖版）
- **配置管理**：导入/导出 JSON 配置；快捷键 `Ctrl/Cmd + S` 导出、`D` 下载、`R` 重置、`B` 切换侧边栏（移动端）
- **多语言**：中英文切换
- **导出**：PNG（推荐）、JPEG、WebP

## 使用方法

本地直接浏览器打开 `index.html`，或通过 GitHub Pages 部署在线访问。

## 技术栈

纯前端实现（HTML5 Canvas + Vanilla JS + CSS3），零第三方依赖，响应式设计。

## 项目结构

```
cover-make/
├── CNAME           # GitHub Pages 自定义域名
├── index.html      # 主页面
├── style.css       # 样式文件
├── script.js       # 核心逻辑
└── README.md       # 项目说明
```

## 添加图标

访问 [yesicon.app](https://yesicon.app) 搜索图标 → 复制 SVG 代码 → 粘贴到"图标"面板，或直接上传 `.svg` 文件。

## 开源协议

MIT License

---

> 用 ❤️ 制作，让封面设计更简单
