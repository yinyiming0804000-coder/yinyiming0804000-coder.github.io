---
layout: post
title: 我的个人博客，从 Markdown 开始
date: 2026-10-24
excerpt: 用 Jekyll、Markdown 和 GitHub Pages，搭建一个可以持续写作的个人空间。
tags:
  - 建站记录
  - Jekyll
---

今天，我开始整理自己的个人博客。这里会记录网页学习、项目实践，以及值得留下的想法。

## 从一个简单的模板开始

这个博客基于 [nice-template](https://github.com/yejianqin61-cell/nice-template)。我保留了模板原有的首页、文章和关于页结构，填入自己的信息，并把页面调整为蓝绿色配色。

项目区先展示这个博客本身，源码放在 [GitHub 仓库]({{ site.repository_url }}) 中。接下来，我会随着实际学习和实践逐渐补充内容。

## 用 Markdown 写文章

文章保存在 `_posts/` 目录，文件名使用 `YYYY-MM-DD-title.md`。每篇文章开头保留标题、日期、摘要和标签等 Front Matter，正文直接使用 Markdown。

对我来说，先把内容写清楚，比增加复杂功能更重要。一篇文章可以只记录一个问题、一次尝试，或者一个终于理解的概念。

## 让发布流程保持简单

博客使用 Jekyll 把 Markdown 转成 HTML。提交并推送到 GitHub 后，GitHub Actions 会构建网站，再部署到 GitHub Pages。构建发生在云端，本地编辑文章和样式即可。

首次发布前，我会检查个人信息、文章链接和修改差异，确认后再提交。以后更新文章也沿用这个流程。

## 接下来想记录的事

- 学习 HTML 和 CSS 时的笔记。
- 调整博客布局、配色与阅读体验的过程。
- 实践中遇到的问题和解决方法。

这个博客从一篇建站记录开始。希望每次回看，都能看到一点新的进步。
