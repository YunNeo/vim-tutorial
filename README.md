# vim-tutorial
The easy way to learn Vim

### 序言
    主要介绍在 vs code 使用 vim 。   
    vim 的视角里，代码 = 单词、 包裹符号、 空行、
    vim 快捷键虽然多，但是都基于简单的规律，按需组合来的
 ## 单词 word = `w`
 ## 包裹符号 sround = `s` 比如:(),{},[]
 ## 空行 pragragh = `p` 

### 基本动作
1. `c` change 
1. `v` vitural
1. `d` delete
1. `y` yank 

### 描述范围 （相对于包裹符号）
1. `i` inside
1. `a` around / all

### 快捷键 通常是一个英文单词的首字母，偶尔会有正则符号
撤销
`u` undo 
`U` redo (大写=反向操作)

进入输入模式
`i` insert before cursor
`a` append after cursor
`I` Insert from end of line (大写=增强)
`A` Append from end of line

`b` back   of the word
`e` end of the word
`0` begin of the line
`^` begin of the line (regex match)
`$` end of the line    (regex match)

### 上手体验

修改一个单词 `c`+`w`
把下面的hello改成hi

  hello world
