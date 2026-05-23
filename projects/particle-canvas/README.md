# 粒子交互画布

基于 Canvas 的粒子系统，展示事件处理与动画性能优化能力。

## 技术栈

- HTML5 Canvas
- CSS3（毛玻璃 / 渐变）
- JavaScript（requestAnimationFrame / 事件系统 / 面向对象）

## 功能特性

- 粒子自动生成，数量根据屏幕大小自适应
- 三种交互模式：吸引、排斥、环绕
- 点击生成粒子爆发效果（带衰减生命周期）
- 粒子间连线（距离检测）
- 粒子光晕效果
- 实时 FPS 与粒子数量统计
- 触摸屏支持（touchmove / touchend）
- 边界反弹物理模拟
- 摩擦力与速度衰减
- 响应式适配（600px 断点）

## 项目结构

```
particle-canvas/
├── index.html    ← 页面结构与粒子逻辑
├── style.css     ← 样式表
└── README.md     ← 项目说明
```

## 预览

在浏览器中打开 `index.html` 即可预览。
