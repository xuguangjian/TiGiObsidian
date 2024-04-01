---
uid: 20220318210057
aliases: []
---
本文是基于[[如何同步obsidian文件（MOC）|λ:/obsidian中文教程/03 教程/如何同步obsidian文件（MOC）]]总结的阶段性文字，有一定时效性。本人能力有限，如有错误请在公众号留言。本文发布后会根据大家的反馈进行修正。中文教程中的UID号为20220318210057。

另外，本人不对以下所有同步方案的安全性、隐秘性负责。请做好数据备份，可参考[[使用Kopia来备份obsidian by 软通达|λ:/obsidian中文教程/01 2021新教程/使用Kopia来备份obsidian by 软通达]]。

# 最佳的同步方式
官方的[[同步（sync核心插件）|λ:/obsidian中文教程/01 2021新教程/同步（sync核心插件）]]服务，具体信息可以参考官方帮助文档：[[Obsidian 同步服务 by ob官方|λ:/obsidian中文教程/06 ob官方帮助文档（节选）/Obsidian 同步服务 by ob官方]]。

优点：省心，全功能。
缺点：贵，目前大部分用户（非早鸟用户）月付是10美元，年付是8美元。

值得讨论的事情：
按我的理解，购买官方同步服务后，一个账号是有5个库，5个库可以分别设置端到端加密。可以5个人共用一个同步账号（共同知道账号的账号的用户名和登陆密码），但分别给自己的同步库设置端到端加密（此密码只有自己知道）。这样能保证其他用户无法访问你的ob同步库，最坏的情况只能是某人将你的同步库在云端删除了，但你还保有本地数据。

最好的解决方法，你将ob推荐给你身边的4个朋友，你们都感觉好用，一起使用一个同步服务，这样就月付2美元，约12人民币。

此想法类似于office 365拼车。

# 替代方案
## 全平台同步方案 ：Remotely save
[[Remotely save（同步插件）|λ:/obsidian中文教程/01 2021新教程/Remotely save（同步插件）]]是本周讨论最火的插件，教程中已经收录了许多内容：
- [[Obsidian 同步 Remotely Save S3 配置指南 by 恐咖兵糖|λ:/obsidian中文教程/01 2021新教程/Obsidian 同步 Remotely Save S3 配置指南 by 恐咖兵糖]]
- [[第三方同步插件（Remotely save介绍） by 软通达|λ:/obsidian中文教程/01 2021新教程/第三方同步插件（Remotely save介绍） by 软通达]]:Dropbox
- [[Obsidian Remotely Save 插件实现电脑和移动端同步 by yaozhuwa|λ:/obsidian中文教程/01 2021新教程/Obsidian Remotely Save 插件实现电脑和移动端同步 by yaozhuwa]]:onedrive方式
- [[最舒服的Obsidian第三方多端同步 by 维客笔记|λ:/obsidian中文教程/01 2021新教程/最舒服的Obsidian第三方多端同步 by 维客笔记]]：Dropbox
- [[remotely插件搭配腾讯云cos教程 by 八宝周|λ:/obsidian中文教程/01 2021新教程/remotely插件搭配腾讯云cos教程 by 八宝周]]：腾讯云，S3
- [[Obsidian通过Remotely save插件实现坚果云同步 by BCS|λ:/obsidian中文教程/01 2021新教程/Obsidian通过Remotely save插件实现坚果云同步 by BCS]]：坚果云，webdav
- [[Obsidian使用Remotely Save 和阿里云 OSS 实现多平台同步 by zm|λ:/obsidian中文教程/01 2021新教程/Obsidian使用Remotely Save 和阿里云 OSS 实现多平台同步 by zm]]：阿里云oss，S3

推荐使用阿里云或腾讯云的s3服务。

## PC和安卓同步
Win和安卓可以考虑[[Syncthing（同步软件）|λ:/obsidian中文教程/01 2021新教程/Syncthing（同步软件）]]或者类似的[[微力同步|λ:/obsidian中文教程/03 教程/微力同步]]。可见[[使用腾讯云搭建Syncthing来同步obsidian by 软通达|λ:/obsidian中文教程/03 教程/使用腾讯云搭建Syncthing来同步obsidian by 软通达]]。

因为笔者没有Mac，不知道此方法MAC是否可以使用，猜测没什么问题。

## Mac和iOS同步
可以考虑[[iCloud|λ:/obsidian中文教程/03 教程/iCloud]]，没有设备，没有尝试。

## 仅电脑之间同步
推荐使用[[坚果云|λ:/obsidian中文教程/01 2021新教程/坚果云]]等同步软件。这里注意2点：
1. 不要两台机同时开着ob和同步软件，这样会导致保存出错。
2. 注意分辨同步盘和储存盘（网盘）的区别。

# 不建议方案
## iCloud做Win和iOS同步
目前接收的信息，win和ios用iCloud同步存在较多问题。但有人提出可以使用[[FreeFileSync|λ:/obsidian中文教程/FreeFileSync]]进行协助可以改善上述问题，[[obsidian好用的icloud同步方案 by 咸的粥|λ:/obsidian中文教程/03 教程/obsidian好用的icloud同步方案 by 咸的粥]]，可以尝试看看。

## 坚果云做PC和手机同步
坚果云会限制API调用，不建议将坚果云作为WebDAV服务来用于手机同步。



