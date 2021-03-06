---
layout: wiki
title: Markdown
categories: Markdown
description: Markdown 常用语法示例
keywords: Markdown
---


外部参考： [MD简明教程](https://ouweiya.gitbooks.io/markdown/index.html)

-------------------------------------------
<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [常用篇](#常用篇)
	- [分级标题](#分级标题)
	- [文字修饰（斜体/加粗）](#文字修饰斜体加粗)
	- [无序列表](#无序列表)
	- [有序列表](#有序列表)
	- [链接](#链接)
	- [内嵌图片](#内嵌图片)
	- [引用块](#引用块)
	- [代码](#代码)

<!-- /TOC -->
------------------------------------

# 常用篇
## 分级标题
> #\~######   h1\~h6  
> 注：标题只有6个等级，#后面有空格
> 示例：
>
> # h1
> ## h2
> ### h3
> #### h4
> ##### h5
> ###### h6
> ####### h7(错误代码)
## 文字修饰（斜体/加粗）
> 使用 \* 和 \*\* 表示斜体和加粗。  
> 示例：
> 这是*斜体*, 这是**加粗**。
>  使用<u\></u\> 处理下划线
> 示例：
> 这是<u>下划线</u>测试
## 无序列表
> 使用 \* + -表示无序列表
> 示例：
>
> * 无序表项一
> * 无序表项二
> * 无序表项三
> ## 有序列表  
> 使用数组和点表示
> 示例：
>
> 1. 有序表项一
> 2. 有序表项二
> 3. 有序表项三
## 链接
> 内链式：
> 使用 \[描述\]\(链接地址\) 为文字增加外链接。链接到同样主机的资源，可以使用相对路径\[about\]\(about.md\).  
> 示例：  
> [baidu](https://www.baidu.com)  
> [baidu2](3)  
[3]:https://www.baidu.com

## 内嵌图片
> 使用 \!\[描述\]\(图片链接地址\) 插入图像。
> 示例：
> ![](../images/wiki/markdown/test.png)
## 引用块
> 使用 \> 符号 表示引用，\>\> 表示多层嵌套
> 示例：
>
> > > > 一行
> > > > 两行(多行时，可以省略引用符号)
>
> > > 多层嵌套
## 代码
> * 单行标记
> 使用 \` 标记单行代码块
> 示例： 这是`hello world`  
> 使用 \`\`\` 标记多行代码块
> 多行代码块示例：
```c
var num = 0;
for (var i = 0; i < 5; i++) {
    num+=i;
}
console.log(num);
```
## TODO列表
使用带有- [ ] 或 - [x] （未完成或已完成）项的列表语法撰写一个待办事宜列表.
示例：

- [ ] todo1
- [x] todo2

## 表格

* 居左：“:---”
* 居中：“:---:”
* 居右：“---:”

| 姓名 | 性别 | 年龄 |
|:---:|:---:|---|
| li | boy |24 |

