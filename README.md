# Yue Zhao 的个人札记

网站默认打开[英文首页](https://yu-zh47.github.io/)，[中文首页](https://yu-zh47.github.io/zh/) 单独列出中文文章。GitHub Pages 会在 `main` 分支更新后自动发布。

## 写下一篇

在 GitHub 打开[英文文章目录](_posts/)或[中文文章目录](zh/_posts/)，选择 **Add file → Create new file**。文件名用日期和英文短名，例如 `2026-11-20-reading-notes.md`。把下面几行放在开头，空一行后直接写正文。标题、分类和摘要使用文章的语言。

```markdown
---
title: "文章标题"
topic: 随笔
description: "在首页显示的一句摘录。"
---

第一段正文。

## 小标题

下一段正文。
```

点 **Commit changes** 保存到 `main`。对应语言的首页会按日期列出文章。文件名里的英文短名决定文章网址，例如英文版会发布到 `/writing/reading-notes/`，中文版会发布到 `/zh/writing/reading-notes/`。

同一篇文章有两种语言时，在两个目录中使用相同的文件名。在英文版开头的两行 `---` 之间加入 `translation_url: /zh/writing/reading-notes/`，在中文版加入 `translation_url: /writing/reading-notes/`。页面顶部的语言链接就会指向同一篇文章的另一版。
