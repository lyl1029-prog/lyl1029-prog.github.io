# Personal Portfolio Website

一个现代化的个人作品集网站，展示作品、视频、项目和关于我。

## 功能特性

- 📸 作品展示（瀑布流布局）
- 🎬 视频作品展示
- 📋 项目列表
- 👤 关于我页面
- 📱 响应式设计
- 🌙 优雅的动画效果

## 部署说明

此网站已准备就绪，可部署到 GitHub Pages。

## 本地运行

由于网站使用 JavaScript 动态加载数据，需要通过本地服务器运行：

### 使用 Python
```bash
python -m http.server 8000
```

### 使用 Node.js
```bash
npx http-server
```

然后在浏览器中访问 `http://localhost:8000`

## 更新内容

网站内容通过 `data/` 目录中的 JSON 文件管理：
- `site.json` - 网站基本信息
- `works.json` - 作品集
- `videos.json` - 视频作品
- `projects.json` - 项目列表

更新这些文件后，刷新页面即可看到效果。

---

部署到 GitHub Pages 后，你将拥有一个免费的个人网站！
