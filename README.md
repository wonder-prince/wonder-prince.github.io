# Wang Zinuo · Interstellar Lab

王子诺的个人主页，使用 Astro 构建并通过 GitHub Pages 发布。

## 本地开发

```bash
npm install
npm run dev
```

## 构建检查

```bash
npm run build
npm run preview
```

## 内容位置

- `src/pages/index.astro`：首页
- `src/pages/about.astro`：个人介绍
- `src/pages/blog/index.astro`：文章索引
- `src/content/blog/`：后续迁移的新文章
- `public/2025/`：从旧站保留的历史文章
- `public/images/`：图片素材
- `public/files/`：PDF 等文件

推送到 `main` 后，`.github/workflows/deploy.yml` 会自动构建并部署网站。
