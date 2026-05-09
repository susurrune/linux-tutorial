# Linux 命令行艺术 🐧

> 一个精心设计的交互式 Linux 教程网页，将技术文档转化为视觉体验。

[![Linux](https://img.shields.io/badge/Linux-Tutorial-oklch(70%25%200.15%20195)?style=flat-square)](https://github.com/susurrune/linux-tutorial)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-oklch(70%25%200.15%20195)?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

## ✨ 设计特点

本教程采用 **Web Design Engineer** 技能构建，遵循现代网页设计最佳实践：

- 🎨 **oklch 色彩系统** — 感知均匀的色彩空间，确保视觉一致性
- 🔤 **精选字体组合** — Space Grotesk + Inter + JetBrains Mono
- 📐 **非对称网格布局** — 杂志编辑风格的不对称卡片系统
- 📱 **全面移动端优化** — 汉堡菜单、触摸适配、刘海屏支持
- 🔍 **SEO 优化** — Schema.org 结构化数据、Open Graph、Twitter Cards
- 📊 **滚动进度条** — 顶部进度指示器，实时反馈阅读进度
- 💫 **精致动效** — 滚动触发动画和悬浮交互
- 🌙 **深色主题优先** — 保护眼睛的科技风格深色界面
- ♿ **可访问性** — 符合 WCAG 对比度标准
- ⚡ **性能优化** — 减少动画偏好支持、触摸设备优化、触觉反馈

## 🚀 在线预览

🔗 **GitHub Pages**: https://susurrune.github.io/linux-tutorial

## 📚 内容结构

| 模块 | 主题 | 命令 |
|------|------|------|
| **Module 01** | 文件与目录 | `pwd`, `ls`, `cd`, `touch`, `mkdir`, `cp`, `mv`, `rm` |
| **Module 02** | 权限与进程 | `chmod`, `chown`, `ps`, `top`, `htop`, `kill` |
| **Module 03** | 网络诊断 | `ip`, `ping`, `traceroute`, `dig`, `ss`, `curl`, `wget` |
| **Module 04** | 文本与工具 | `grep`, `sed`, `awk`, `apt`, `dnf`, `pacman` |

## 🛠️ 本地使用

```bash
# 克隆仓库
git clone https://github.com/susurrune/linux-tutorial.git

# 进入目录
cd linux-tutorial

# 直接在浏览器打开
open index.html
# 或
firefox index.html

# 或使用 Python 简单服务器
python3 -m http.server 8080
# 访问 http://localhost:8080
```

## 📱 移动端优化

针对手机和平板设备的专门优化：

### 导航体验
- 🍔 **汉堡菜单** — 点击展开全屏导航
- 👆 **触摸优化** — 点击反馈、防误触
- 📐 **安全区域** — 适配刘海屏、灵动岛

### 视觉适配
- 📏 **动态字号** — 根据屏幕自动调整
- 🎯 **间距压缩** — 小屏幕更紧凑布局
- ↔️ **代码滚动** — 横向滚动提示

### 性能优化
- ⚡ **减少动画** — 移动端简化动效
- 🖐️ **触摸反馈** — 点击时的缩放反馈
- 🔋 **节能模式** — `prefers-reduced-motion` 支持

### 断点设计
- **375px** — 超小屏优化
- **768px** — 手机/平板切换
- **1024px** — 平板/桌面切换

## 🎯 交互功能

- 📋 **点击复制** — 点击任意代码块即可复制到剪贴板
- 🌗 **主题切换** — 支持深色/浅色模式切换
- 🔗 **平滑滚动** — 导航栏支持平滑滚动到对应章节
- ✨ **动画效果** — 滚动触发的渐入动画

## 🎨 设计系统

### 色彩方案 (oklch)
```css
--color-bg: oklch(12% 0.02 260);         /* 深海蓝背景 */
--color-primary: oklch(70% 0.15 195);    /* 电光青强调 */
--color-accent: oklch(75% 0.18 145);     /* 翠绿点缀 */
--color-text: oklch(95% 0.01 260);       /* 高对比文字 */
```

### 字体层级
- **标题**: Space Grotesk (几何无衬线，现代感)
- **正文**: Inter (高可读性界面字体)
- **代码**: JetBrains Mono (等宽，编程专用)

### 布局原则
- 12 列非对称网格系统
- 大留白呼吸感设计
- 卡片悬浮阴影层次
- 微妙边框和发光效果

## 🏗️ 技术细节

- **纯 HTML/CSS/JS** — 零依赖，单文件部署
- **CSS Custom Properties** — 动态主题系统
- **CSS Grid + Flexbox** — 现代布局方案
- **Intersection Observer** — 高性能滚动动画
- **CSS oklch()** — 感知均匀色彩空间
- **SEO 优化** — Schema.org 结构化数据、Open Graph、Twitter Cards
- **自动部署** — GitHub Actions 自动部署到 GitHub Pages
- **触觉反馈** — 移动端代码复制时的振动反馈
- **键盘快捷键** — ESC 关闭菜单，支持未来扩展
- **安全区域** — 刘海屏、灵动岛适配

## 🚀 自动部署

本仓库已配置 GitHub Actions 自动部署：

1. 推送代码到 `main` 分支
2. GitHub Actions 自动运行
3. 自动部署到 GitHub Pages

查看部署状态: [Actions 页面](../../actions)

## 📖 设计参考

本项目使用 [Web Design Engineer](https://github.com/susurrune/web-design-skill) 技能构建，该技能源自 Claude Design 的系统提示，提供：

- ✅ 反 AI 设计 cliché 指南
- ✅ oklch 色彩理论应用
- ✅ 精心策划的字体搭配
- ✅ 结构化设计工作流程

## 🤝 贡献

欢迎提交 Issue 和 PR！特别是：
- 🐛 命令错误或过时
- 🎨 设计改进建议
- 🌍 多语言支持
- ♿ 可访问性改进

## 📄 许可证

MIT License © 2025 [susurrune](https://github.com/susurrune)

---

<p align="center">
  Made with precision using Web Design Engineer Skill
</p>
