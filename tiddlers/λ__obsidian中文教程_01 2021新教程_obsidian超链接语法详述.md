obsidian超链接语法详述 by [[Ryooo|λ:/obsidian中文教程/07 信息源与贡献者/Ryooo]]
ob的插入基于markdown的插入图片和插入链接衍生。
### 图片
`[img [图片替代文字|图片地址]]`语法是可取的，ob支持用这种方式插入网络图片，但是本地图片似乎只支持vault内的图片。
ob默认以`{{λ:/obsidian中文教程/}}`的形式插入图片，并在当前页面中显示。
ob支持`[[Pasted image 256.png|λ:/obsidian中文教程/Pasted image 256.png]]`插入vault内的图片，图片不一定需要在附件文件夹中。但是这样是不显示的。、

### 链接
ob支持`[链接文字](链接地址 "Title")`，需要注意的是如果链接文字为空链接是不显示的。ob也支持[[自动连接|λ:/obsidian中文教程/Markdown#自动连接]]	。

### note
`[[|λ:/obsidian中文教程/]]`以link的形式插入note。这个可以通过`[[filename#header|λ:/obsidian中文教程/filename#header]]`的方式引用到更细的层级，也可以用`[[代替文本|λ:/obsidian中文教程/filename]]`的方式进行文本替换
`{{λ:/obsidian中文教程/}}`会将插入的note显示在当前页，类似图片。这个等价于`![](note名字)`
`[链接文字](note name)`会以链接方式插入note。这个和`[[|λ:/obsidian中文教程/]]`不同在于，这种方式不会自动显示note名字，需要在链接文字中填写。

### 文件
`[文字](file:///文件路径)`可以打开本地文件，路径中需要使用`/`，文件名需要全英文，空格需要重编码成%20。目前只支持绝对路径
[猫](file:///D:/Providing%20NotesForReview.docx)