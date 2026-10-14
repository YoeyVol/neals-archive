# NEALS 年会公开档案浏览器

一个纯静态网站，按年份浏览 NEALS 1995–2026 年会公开档案索引。页面从同目录的 `archive-data.json` 读取记录，并使用 `assets/neals-2023-meeting.jpg` 作为首页缩略图。

## 本地预览

可用任意静态文件服务器从仓库根目录提供文件；请勿直接以 `file://` 打开，因为页面通过 `fetch()` 加载 JSON。

## GitHub Pages

部署地址：<https://yoeyvol.github.io/neals-archive/>

GitHub Pages 从 `main` 分支根目录提供静态文件，无需构建步骤。
