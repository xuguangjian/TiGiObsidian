#### 202008221716 by [[海歌|λ:/obsidian中文教程/07 信息源与贡献者/海歌]]
 你在css中 搜索.cm 添加到下边
可以
保存后就生效了
 别添加到别的代码{}符号内就行。
别的没什么 
[img [202008271240.png]]
```
 .cm-hmd-list-indent .cm-tab, ul ul { position: relative; }
.cm-hmd-list-indent .cm-tab::before, ul ul::before {
 content:'';
 border-left: 1px solid rgba(0, 122, 255, 0.25);
 position: absolute;
}
.cm-hmd-list-indent .cm-tab::before { left: 0; top: -5px; bottom: -4px; 
}
ul ul::before { left: -11px; top: 0; bottom: 0; 
} 
```

####  202008221718无序列表的点改实心 by [[paprika|λ:/obsidian中文教程/07 信息源与贡献者/paprika]]
```
ul {

  list-style-type: circle;

}
```
[[船长|λ:/obsidian中文教程/07 信息源与贡献者/船长]]试了可以，实心要把circle改成disc  https://www.w3schools.com/cssref/pr_list-style-type.asp
图片: 
[img [202008271242.png]]
 
 #### 202008221838 小总结 by [[怀揣可爱|λ:/obsidian中文教程/07 信息源与贡献者/怀揣可爱]]
 [img [202008271243.png]]
 实现技巧：
- 在css中搜索 .cm,并添加以下代码到代码块的下边 #CSS
- 代码：
```
.cm-hmd-list-indent .cm-tab, ul ul { position: relative; }
.cm-hmd-list-indent .cm-tab::before, ul ul::before {
 content:'';
 border-left: 1px solid rgba(0, 122, 255, 0.25);
 position: absolute;
}
.cm-hmd-list-indent .cm-tab::before { left: 0; top: -5px; bottom: -4px; 
}
ul ul::before { left: -11px; top: 0; bottom: 0; 
}

/*可以将list前的空心圆改成实心，若要改成全空心，则将disc改成circle*/
ul{
list-style-type: disc;
}
```