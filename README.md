# 我的个人网站

基于 [Astro](https://astro.build/) 搭建的多领域个人网站项目骨架。

## 项目简介

这是一个以 Astro 框架为基础的个人网站，利用 Astro 的 Islands Architecture 和多框架混用能力，支持在同一个网站内为不同领域的内容（如摄影、读书笔记、游戏收藏等）设计完全独立的 UI 风格。

## 目录结构

```
src/
  layouts/
    BaseLayout.astro     # 全站统一的导航/页脚外壳布局
  pages/
    index.astro          # 首页，展示欢迎信息及各板块入口
  components/            # 预留目录，后续按领域添加子目录
  content/               # 预留目录，后续用于 Content Collections
```

## 本地开发

```bash
npm install
npm run dev
```

浏览器访问 `http://localhost:4321` 查看效果。

## 构建

```bash
npm run build
npm run preview
```

## 技术栈

- [Astro](https://astro.build/) — 静态站点生成框架，支持 Islands Architecture
- TypeScript（strict 模式）
