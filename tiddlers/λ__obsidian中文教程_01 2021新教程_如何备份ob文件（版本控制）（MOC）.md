---
title: 
uid: 202107282159
aliases: []
tags: []
from: 
---
# 引言
obsidian作为一款笔记软件，里面汇聚了我们的心血，数据不易，注意备份。本文从4个方面介绍了如何回复ob的数据，或者说得专业一些是版本控制，大家如果有更好的点子，请留言。
本文的双链版本发布在ob中文教程中，uid号是202107282159。如果你在微信公众号内阅读，可能会无法点击双链，请访问ob教程。

# ob软件本体
最简单的方式是使用ob软件自带的“文件恢复”插件，具体可见[[obsidian内置文件恢复（File Recovery功能介绍） by 软通达|λ:/obsidian中文教程/01 2021新教程/obsidian内置文件恢复（File Recovery功能介绍） by 软通达]]。但快照存在有时间限制（可以自己设置，例如7天），并且仅能恢复本节的修改。
如果你购买了官方同步服务（见[[obsidian同步服务（设置篇） by 软通达|λ:/obsidian中文教程/03 教程/obsidian同步服务（设置篇） by 软通达]]、[[obsidian同步服务（体验篇） by 软通达|λ:/obsidian中文教程/03 教程/obsidian同步服务（体验篇） by 软通达]]），则可以使用同步服务内的“已删除文件”来恢复。此功能相比“文件恢复”，可以多端进行恢复，并且快照存在时间更长。

# ob第三方插件
强烈推荐使用[[git|λ:/obsidian中文教程/01 2021新教程/git]]来进行版本控制，但有一定的技术门槛。还可以搭配[[Obsidian Git （版本控制插件）|λ:/obsidian中文教程/01 2021新教程/Obsidian Git （版本控制插件）]]，见[[obsidian和Git连用实现版本控制（obsidian Git插件介绍） by 软通达|λ:/obsidian中文教程/01 2021新教程/obsidian和Git连用实现版本控制（obsidian Git插件介绍） by 软通达]]。

# 同步软件
许多用户会使用第三方的同步软件（[[如何同步obsidian文件（MOC）|λ:/obsidian中文教程/03 教程/如何同步obsidian文件（MOC）]]），例如
- [[坚果云|λ:/obsidian中文教程/01 2021新教程/坚果云]]
- [[OneDrive|λ:/obsidian中文教程/01 2021新教程/OneDrive]]
- [[seafile|λ:/obsidian中文教程/01 2021新教程/seafile]]
- [[Syncthing（同步软件）|λ:/obsidian中文教程/01 2021新教程/Syncthing（同步软件）]]
- [[使用Kopia来备份obsidian by 软通达|λ:/obsidian中文教程/01 2021新教程/使用Kopia来备份obsidian by 软通达]]

这些软件都有版本控制功能，如有不懂请查看这些软件的帮助文档，向社区询问，向开发者或客服寻求帮助。

# 本地备份软件
用户也可以使用本地的备份软件对数据进行备份，例如拷贝一份数据到其他存储介质上（例如U盘）。这类软件也很多，例如[[Goodsync|λ:/obsidian中文教程/01 2021新教程/Goodsync]]、[[Acronis True Image|λ:/obsidian中文教程/01 2021新教程/Acronis True Image]]、[[Iperius Backup|λ:/obsidian中文教程/01 2021新教程/Iperius Backup]]等等，如有不懂也请查看这些软件的帮助文档，向社区询问，向开发者或客服寻求帮助。
可能还需要考虑是双向备份、镜像备份、增量备份等备份策略，推荐使用增量备份。

