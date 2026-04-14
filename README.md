# EngineerX96.github.io

个人 GitHub Pages 博客，用于记录技术心得、学习笔记与个人分享。

🌐 **站点地址**：[https://engineerx96.github.io](https://engineerx96.github.io)

## 本地运行

```bash
gem install bundler jekyll
bundle exec jekyll serve
```

浏览器访问 `http://localhost:4000`

## 新增文章

在 `_posts/` 目录下创建 `YYYY-MM-DD-title.md` 文件，文件头格式：

```yaml
---
layout: post
title: "文章标题"
date: 2026-01-01 00:00:00 +0800
tags: [标签1, 标签2]
excerpt: "文章摘要（可选）"
---
```

## 技术栈

- [Jekyll](https://jekyllrb.com/) 静态站点生成器
- 纯 CSS 自定义主题（深色风格）
- GitHub Pages 托管