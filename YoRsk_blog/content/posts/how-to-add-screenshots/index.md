---
title: 如何在博客里插入截图（两种方法）
date: 2026-08-29T14:00:00+09:00
draft: false
summary: ''
tags: []
showToc: true
---

## 方法一：Page Bundle（推荐）

图片和文章放在同一个文件夹里，文章文件名必须是 `index.md`：

```plain
content/posts/how-to-add-screenshots/
├── index.md            ← 文章
└── terminal-demo.png   ← 截图
```

引用时直接写文件名：

```markdown
![终端截图](terminal-demo.png)
```

效果如下：

![](20260830-174108.png)


![1](ScreenShot_2026-08-29_142636_084.png)

## 

## Windows 截图小技巧

按 `Win + Shift + S` 框选截图 → 打开"画图"或直接 `Ctrl+V` 到聊天窗口再另存，
最简单的做法是：截图后打开 **PowerToys**（或 Snipping Tool 的"另存为"），
把文件保存到文章文件夹里即可。

现在有了 /admin 后台，还可以直接在浏览器里粘贴截图发布。
