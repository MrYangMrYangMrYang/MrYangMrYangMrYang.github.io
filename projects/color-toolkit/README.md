# 色彩工具箱

HSL 选色器与配色工具，展示 Web API 与产品思维。

## 技术栈

- HTML5
- CSS3（Grid / 自定义滑块 / 渐变）
- JavaScript（HSL/RGB/Hex 色彩转换 / WCAG 对比度计算 / Clipboard API）

## 功能特性

- **颜色选择器**：HSL 三轴滑块，实时预览，4 种格式输出（HEX/RGB/HSL/RGBA），一键复制
- **调色板生成器**：5 种配色方案（类似色/互补色/三角色/分裂互补/单色），点击色块复制色值
- **对比度检测**：前景/背景色选择，WCAG 2.1 标准检测（AA/AAA 正文与大字），实时预览
- 色彩空间转换（HSL ↔ RGB ↔ Hex）
- 相对亮度计算与对比度比值
- Toast 提示反馈
- 响应式适配（768px / 480px 断点）

## 项目结构

```
color-toolkit/
├── index.html    ← 页面结构与色彩逻辑
├── style.css     ← 样式表
└── README.md     ← 项目说明
```

## 预览

在浏览器中打开 `index.html` 即可预览。
