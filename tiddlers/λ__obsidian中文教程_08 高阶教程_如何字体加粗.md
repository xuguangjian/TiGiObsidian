202008221357加粗字体 by [[floatingriver|λ:/obsidian中文教程/07 信息源与贡献者/floatingriver]]
找到加粗字体的方法了：主题文件中增加这两段可以分别加粗编辑模式和预览模式下的粗显文字到最粗；预览模式下本来就是bold（700）了，加到900其实看不啥变化的，所以结论是最好不要在暗黑模式下阅读有粗体的文字
```
 .cm-s-obsidian .cm-header,
.cm-s-obsidian .cm-strong {
  font-weight: 900;
}

strong {

  font-weight: 900;

} 
```

202008221401通过颜色指代不同的格式 From [[姚|λ:/obsidian中文教程/07 信息源与贡献者/姚]] 
可以用不用颜色来表征正常、斜体和加粗字体，而不是像素的变化。

202008221404通过不同字体指代不同的格式 From [[蚕子|λ:/obsidian中文教程/07 信息源与贡献者/蚕子]]
例如，正常字体设为Microsoft Yahei，加粗字体设为
Microsoft YaHei Light
```
.cm-s-obsidian .cm-header,
.cm-s-obsidian .cm-strong {
  font-weight: 900;
  font-family: Microsoft YaHei Light;
}
```

