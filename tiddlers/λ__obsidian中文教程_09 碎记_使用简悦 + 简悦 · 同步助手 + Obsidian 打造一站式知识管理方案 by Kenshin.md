---
title: 
uid: 202012291543
aliases: []
tags: []
from: 
---
 [[重点文章|λ:/obsidian中文教程/01 2021新教程/重点文章]]
原文地址：http://kenshin.wang/blog/#/posts/25
[[Kenshin|λ:/obsidian中文教程/07 信息源与贡献者/Kenshin]]论述了[[简悦|λ:/obsidian中文教程/01 2021新教程/简悦]]和obsidian的连用，经作者本人同意，进行了转载。
预先说明：[[Kenshin|λ:/obsidian中文教程/07 信息源与贡献者/Kenshin]]是[[简悦|λ:/obsidian中文教程/01 2021新教程/简悦]]的开发者
[[68747470733a2f2f73332e617831782e636f6d2f323032302f31322f32392f72486a4b64312e706e67|λ:/obsidian中文教程/img [https://camo.githubusercontent.com/c4549bc24b2f5d97007f0a495fc1c65c4b74c662d3aa47ec6cdb4a94f8a9a73e/68747470733a2f2f73332e617831782e636f6d2f323032302f31322f32392f72486a4b64312e706e67]]](https://imgchr.com/i/rHjKd1)

> 知识管理有很多中方式，这里提一种： **如何通过简悦 + Obsidian 进行拆书** 。

### 优势

> 简悦 2.1 与 Obsidian 都可以基于本地系统，所以 **你的数据你掌握，且放在你需要的地方** ，进行全平台同步。

### 什么是拆书

> 拆书就是转述者或讲书人能把书中的内容、精华提炼出来，然后将原著的中心思想和精华表达具体清楚；而对于我来说，拆书相当于一种将书看薄看熟练的过程。 via [利用 Obsidian 拆书](https://zhuanlan.zhihu.com/p/338719525)

### 准备工作

1.  简悦需要 **[高级账户](https://simpread.pro/price.html)** 
2.  配置并运行 **[简悦 · 同步助手](http://ksria.com/simpread/docs/#/Sync)** 
3.  需将 **[简悦 · 同步助手导出服务](http://ksria.com/simpread/docs/#/Sync?id=%E5%AF%BC%E5%87%BA%E6%9C%8D%E5%8A%A1)** 的文件夹设置为 Obsidian 库文件夹（或其子文件夹）

### 思路如下

1.  在网页使用简悦的标注进行快速标注（简悦支持连续标注），而这个过程类似拆书。
2.  之后将这些快速标注的内容通过 [简悦 · 同步助手](http://ksria.com/simpread/docs/#/Sync?id=%E5%AF%BC%E5%87%BA%E6%9C%8D%E5%8A%A1) 导出到 Obsidian 的目录（以 Markdown 的形式）
3.  同时在标注时，也可以做一些备注，标签的操作（如果只是快速拆书的话，这些可后期再做），甚至于可以将某条标注单独导出。
4.  快速标注后，会在简悦的稍后读生成一个基于标注的页面，在这个页面可以集中管理这些标注，以便做二次修改（补充），同时这些内容也可以导出为 Markdown。
5.  最后每天通过这种方式产生的稍后读（标注）会已邮件汇总的方式发给你指定的邮箱（需配置），用于当天的 [加深回顾](http://ksria.com/simpread/docs/#/%E6%AF%8F%E6%97%A5%E5%9B%9E%E9%A1%BE)。
6.  这篇稍后读（包含若干通过拆书而产生的标注）也可以通过 发送邮件 / 发送到 Kindle / 导出的 PDF 的形式 / 导出 Epub 的形式来辅助你对这篇文章的加深记忆。

### 相比其它标注功能

> 因为上面提到了标注，所以跟其它标注功能相比。

1.  简悦支持单条标注导出（包括：导出到本地和其它生产力工具），所以省去了 **复制 / 粘贴** 的操作。
    
2.  简悦的数据文件都在本地（稍后读和配置文件），所以与 Obsidian 天然搭配。
    

### 利用简悦补齐 KPM 前几个环节

因为很喜欢 Obsidian 所以多说点 **方法论** 的事情。 😀

> 一般来说使用 Obsidian 都是为了补齐 PKM 中的最后一环： **内化** 

而 KPM 的前几个环节： **信息的收集** 和 **信息的过滤** （有效信息）我一般都使用了下面的方案：

1.  使用 Inoreader 过滤功能来筛除一批无效的噪音。via [XDash Weblog](http://xdash.one/use-inoreader-to-filter-news.html)
    
2.  留下来的自然是需要的内容（信息）。
    

> 通过简悦 2.1 提供的 [RSS 阅读器辅助方式](http://ksria.com/simpread/docs/#/RSSReader) 或 [此方式](https://github.com/Kenshin/simpread/discussions/1559) 将这类信息直接导入到简悦的稍后读。

3.  这些信息（还不能称之为知识），大致包括如下几类：
    
    *   只是个人感兴趣的信息，但不具有反复理解的内容。
        
        > 我会把它们通过简悦 [发送到邮件](http://ksria.com/simpread/docs/#/Sync?id=%e9%82%ae%e4%bb%b6%e6%9c%8d%e5%8a%a1)，利用碎片时间在手机上阅读（阅读后会删除它，因为只是用来阅读。（当然，觉得有意义的话，可以使用离线 HTML 的方式，将它永久的保存下来。
        
    *   有意义的信息
        
        > 通过上面描述的拆书方式，发送到 Obsidian 做以后 **内化** 用（内化的结果是：将这些信息转换为你的知识
        
    *   零碎但具有收集意义的信息
        
        > 比如：我要去旅行，在这个前提下，会收集旅行相关的内容，这些内容并不具有知识的属性，但确实是你需要的内容，且它们都分散在不同的页面。
        
        > 遇到这种情况的话，我会通过简悦 [合辑的功能](http://ksria.com/simpread/docs/#/%E7%A8%8D%E5%90%8E%E8%AF%BB?id=%e5%90%88%e8%be%91) 将有需要的内容整理到一个 **页面** ，[这是一个合辑的例子](https://simpread.pro/s/z2Axt6i1)
        
        > 同样即便是合辑，也支持稍后读的全部操作，如：导出 Markdown 等等
        

### 使用简悦如何进行卢曼的卡片笔记法 （Zettelkasten）：

> Zettelkasten 将笔记分为以下几个方面：

1.  Fleeting notes → 阅读资料，并在过程中高亮或者会随手记下临时笔记
2.  Literature notes → 将高亮的部分或者临时笔记总结为文献笔记
3.  Permanent notes → 用自己的话将文献笔记转述为永久笔记

> 实现它们的思路：

1.  Fleeting notes → 简悦的标注
2.  Literature notes → 简悦的合辑（或对某个稍后读的多个标注进行详细备注的操作，简悦的标注与稍后读具有一样的地位和结构）
3.  Permanent notes → 使用 Obsidian

### 最后

在这里只是抛砖引玉的说了下 简悦 与 Obsidian 的配合方案，这也仅仅只是其中一种而已。因为简悦 与 Obsidian 都天然支持本地文件系统，所以基于此可以实现更多的联动，欢迎有更多关于此的使用方案。

