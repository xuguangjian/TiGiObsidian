[[Boninall|λ:/obsidian中文教程/07 信息源与贡献者/Boninall]]
将这个添加到你的 css 文件中
会隐藏你所有的标记
而且保持原有的效果

使用前
[img [202009031143.png]]
使用后
[img [202009031144.png]]

```
/* inline formatting, link targets and [[ |λ:/obsidian中文教程/ ]] disappears if not active line*/
div:not(.CodeMirror-activeline) > .CodeMirror-line span.cm-formatting,
div:not(.CodeMirror-activeline) > .CodeMirror-line span.cm-string.cm-url,
div:not(.CodeMirror-activeline) > .CodeMirror-line span.cm-formatting-link
{ display: none; }

/* hide all html tags -- IT IS COMMENTED OUT BY DEFAULT */
/* div:not(.CodeMirror-activeline) > .CodeMirror-line span.cm-tag{ display: none; } */


/* except list markers */ span.cm-formatting-list,
/*code block backticks */ span.cm-formatting-code-block.cm-hmd-codeblock,
/* optionally header hashes */ span.cm-formatting-header
{ display: inline !important; }

/* and task checkboxes */
span.cm-formatting-task { display: inline !important; font-family: monospace; }
```
