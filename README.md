# HK · 个人在线简历

> 浪尖儿社区训练营必做题作品 —— AI 原生风格个人单页简历

## 在线访问

**线上地址**：https://fklnk.github.io/-/

> 仓库同步托管于 GitHub Pages，PC / 移动端均可直接访问。

## 项目简介

一份以「暗黑极客风 + 霓虹绿点缀」为主视觉的单文件 HTML 简历，具备完整的响应式布局与交互体验：

- **8 大板块**：关于我 / 技能档案 / 证书集 / 重点项目 / 视觉追焦 / AI 实战 / 蓝图工坊 / 联系方式
- **18 项官方认证证书墙**：分类筛选 + 缩略图 + Lightbox 原图查看 + 防伪编号复制
- **AI 蓝图工坊**：本地蓝图引擎（领域模板 + 关键词匹配），离线生成 MVP 架构方案
- **AI 对话分身**：本地知识库问答，模拟本人口吻介绍项目与技能
- **WebGL 着色器背景**、Canvas 礼花粒子、打字机、滚动视差等动效
- **背景音乐**：页面加载自动播放，支持手动暂停/续播

## 技术栈

| 类别 | 选型 |
| --- | --- |
| 结构 | 单文件 HTML5 语义化布局 |
| 样式 | Tailwind CSS（CDN）+ 自定义 CSS 动画 |
| 交互 | 原生 JavaScript（模块化注释，15+ 独立功能块） |
| 图形 | Canvas 2D 粒子系统 / WebGL Shader / Three.js |
| 图标 | Font Awesome 6 |
| 部署 | GitHub Pages |

## 本地运行

无需构建，直接用浏览器打开 `index.html` 即可；推荐通过本地服务器体验完整功能：

```bash
python -m http.server 8000
# 访问 http://localhost:8000
```

## 文件结构

```
├── index.html              # 简历主页面（含全部样式与脚本）
├── hero-bg.jpg             # 涟漪交互背景图
├── ogl.bundle.js           # OGL WebGL 运行时（涟漪背景依赖）
├── AI1.png ~ AI3.png       # AI 编程实战卡片悬停展示图
├── cert-01 ~ 18.png        # 18 项官方认证证书原图
├── bgm.mp3                 # 背景音乐
└── README.md
```

## 作者

**胡坤 (HU KUN)** · 电子科技大学成都学院 · 计算机科学与技术

- GitHub：[@fklnk](https://github.com/fklnk)
- 信条：先完成，再完美。
