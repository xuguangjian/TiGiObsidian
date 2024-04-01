[[flying fly flies|λ:/obsidian中文教程/07 信息源与贡献者/flying fly flies]] [[CSS|λ:/obsidian中文教程/01 2021新教程/CSS]]
取消编辑状态下的高亮
```
/*focus模式，高亮取消*/
/*
.cm-s-obsidian div:not(.CodeMirror-activeline) > .CodeMirror-line span.cm-formatting-highlight,
.cm-s-obsidian div:not(.CodeMirror-activeline) > .CodeMirror-line span.cm-highlight {
  background-color: transparent;
}
.CodeMirror-activeline {
  opacity:1;
} 
*/

```