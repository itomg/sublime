sublime
=======

My Sublime Text 2/3

## [Install Package Control](https://sublime.wbond.net/installation)

## Plugin List:
```
Alignment
BracketHighlighter
CoffeeScript !install in 3
CSS Less !install in 3
CTags !install in 3
DocBlockr
Emmet
Emmet Css Snippets !install in 3
Encoding​Helper != 3
File​Diffs
Git
Github Tools != 3
HTML5 !install in 3
InputHelper != 3
    ctrl + shift + z 输入中文
JavaScript Console
JavaScript Snippets
Java​Script & Node​JS Snippets
jQuery
JsFormat
JSLint != 3
JsMinifier != 3
LESS !install in 3
Markdown preview
Php​Tidy != 3
Phpcs
Prefixr != 3
SFTP
SideBarEnhancements
SideBarGit
SublimeCodeIntel
SublimeLinter != 3
TrailingSpaces
Theme - Soda
```

## User Preferences Settings
```json
## ST2
{
  "color_scheme": "Packages/User/colour-schemes/Monokai Soda.tmTheme",
  "theme": "Soda Dark.sublime-theme",
  "trim_trailing_white_space_on_save": 1,
  "highlight_line": true, // 高亮光标所在行
  "caret_style": "phase" // 光标闪动方式
}
## ST3
{
  "ignored_packages":
  [
    "Vintage"
  ],
  "theme": "Soda Dark 3.sublime-theme",
  "color_scheme": "Packages/User/colour-schemes/Monokai Soda.tmTheme",
  "soda_classic_tabs": true,
  "soda_folder_icons": true,
  "trim_trailing_white_space_on_save": 1,
  "highlight_line": true, // 高亮光标所在行
  "caret_style": "phase" // 光标闪动方式
}
```

## User JavaScript & JSON Settings
```json
{
  "tab_size": 2,
  "translate_tabs_to_spaces": true
}
```

## DocBlockr
```json
{
  // The mid-line characters to align in a multi-line selection, changing
  // this to an empty array will disable mid-line alignment
  "alignment_chars": ["=", ":"],

  "jsdocs_align_tags": "shallow",

  "jsdocs_extra_tags": ["@author Jimmy ({{date}})"],

  "jsdocs_extra_tags_go_after": true,

  "jsdocs_spacer_between_sections": true
}
```

## 无干扰模式(Distraction Free Mode)
```
现在的编辑器如果没有一个无干扰模式似乎都说不过去了，在 Sublime Text 2 中，只要按下 Control + Shift + Command + F 或是在菜单 View 中选择 Enter Distraction Free Mode 就可以进入这个 UI 最小化模式了。如果是在用 Mac OS X Lion 的话，Sublime Text 2 还同时支持 Lion 的原生全屏模式。
通过修改 “Preferences” -> “Settings - More” -> “Distraction Free - User” 可以对防干扰模式进行一些设置：
{
    "line_numbers": false,      //是否显示行号
    "gutter": false,            //是否显示边列
    "draw_centered": true,      //是否居中显示
    "wrap_width": 80,           //换行宽度(单位：字符)
    "word_wrap": true,          //是否自动换行
    "scroll_past_end": true     //滚动能否超过结尾
}
```
