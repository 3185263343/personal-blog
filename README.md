# 个人博客

这是一个基于 Astro + Tailwind 的现代个人博客示例项目，风格偏端庄、简洁与现代感。

## 开发

```bash
npm install
npm run dev
```

## 构建

```bash
npm run build
```

## 部署

Push 到 `main` 分支后，GitHub Actions 会自动构建并部署到 `gh-pages` 分支，随后通过 GitHub Pages 访问。

## 说明

- 首页：`src/pages/index.md`
- 文章列表：`src/pages/posts/index.astro`
- 文章页：`src/pages/posts/post-1.astro`、`src/pages/posts/post-2.astro`
