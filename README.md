# 企业培训练习系统对比分析

蔚来售后 AI 培训学练平台 — 竞品分析与内部实践

## 预览

直接在浏览器打开 `index.html` 即可预览，或访问 GitHub Pages 链接。

## 部署方式

### GitHub Pages（推荐）

1. 在 GitHub 上创建新仓库（仓库名任意，如 `nio-training-comparison`）
2. 将此项目 push 到仓库：
   ```bash
   cd /Users/eric.jiang/Projects/nio-training-comparison
   git init
   git add .
   git commit -m "feat: 企业培训练习系统对比分析 H5 页面"
   git remote add origin git@github.com:<你的用户名>/nio-training-comparison.git
   git branch -M main
   git push -u origin main
   ```
3. 进入仓库 Settings → Pages → Source 选 `Deploy from a branch` → Branch 选 `main` → `/ (root)`
4. 等待部署完成，访问 `https://<你的用户名>.github.io/nio-training-comparison/`

### Vercel / Netlify

直接导入 GitHub 仓库即可，无需额外配置。

## 技术栈

- 单文件 HTML + Tailwind CSS (CDN)
- Google Fonts (Noto Sans SC, Inter)
- 原生 JavaScript，无框架依赖
- CSS Scroll Snap 全屏分页
- IntersectionObserver 入场动画
- localStorage 主题偏好持久化
