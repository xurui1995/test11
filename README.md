# dom-to-pptx Demo

一键将 HTML 幻灯片导出为可编辑 PowerPoint 文件的演示项目，基于 [dom-to-pptx](https://github.com/atharva9167j/dom-to-pptx) 库构建。

## 快速启动（一键命令）

> 前提：已安装 [Node.js](https://nodejs.org/)（v14+）

```bash
npm start
```

命令执行后，浏览器访问 http://localhost:3000 即可看到演示页面。

## 使用方法

1. 运行 `npm start` 启动本地服务
2. 打开浏览器访问 **http://localhost:3000**
3. 点击页面底部的 **"导出为 PowerPoint (.pptx)"** 按钮
4. 浏览器自动下载 `dom-to-pptx-demo.pptx`，用 PowerPoint / WPS / LibreOffice 打开即可编辑

## 演示功能

- 渐变背景 & 复杂阴影（由 dom-to-pptx 精确还原）
- 条形图（纯 HTML/CSS 实现，无 Canvas）
- KPI 数据卡片
- 多色渐变文字
- 圆角元素

## 技术说明

| 项目 | 说明 |
|------|------|
| 服务器 | `serve`（通过 `npx` 自动安装，无需手动安装） |
| 渲染库 | [dom-to-pptx](https://www.npmjs.com/package/dom-to-pptx) via CDN |
| 样式   | Tailwind CSS via CDN |
