---
title: 测试文章：你好，世界
published: 2025-09-22
description: 用于验证主题样式、目录、代码高亮与多语言路由的测试文章。
updated: 
tags: [测试, Hello]
draft: false
pin: 0
toc: true
lang: zh
abbrlink: 
---

> 本文用于快速测试站点是否运行正常：排版、目录、代码高亮、链接与多语言路由等。

## 一、段落与强调

这是普通段落，包含一些文字。可以包含`行内代码`与**加粗**、_斜体_、以及链接到[主页](/)。

## 二、列表

- 无序列表项 A
- 无序列表项 B
  - 子项 B-1

1. 有序 1
2. 有序 2

## 三、代码块

```ts
function greet(name: string): string {
  return `Hello, ${name}!`
}

console.log(greet('World'))
```

## 四、引用与分隔线

> “当你凝视深渊，深渊也在凝视你。”

---

## 五、可选：数学公式（若已开启 KaTeX）

行内示例：令变量满足 $a^2 + b^2 = c^2$。

块级示例：

$$
\int_0^1 x^2\, dx = \frac{1}{3}
$$

## 六、结语

到此，页面应显示目录（若在 `src/config.ts` 中启用）、正确的中文排版与代码高亮。如果需要英文测试，请复制本文件改为 `lang: en` 并调整内容。


