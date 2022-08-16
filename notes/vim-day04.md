### 收获&学习心得&心路历程

目标：更有效率的处理单字符&undo/redo

一、编辑操作

1. `x`删除光标所在字符，`X`删除光标前一个字符
2. `s`删除光标所在字符并进入insert，`S`删除光标所在行并进入insert
3. `r`替换光标所在字符，`R`替换光标开始的多个字符

二、功能

- 可撤销块：进⼊插⼊模式开始，直到返回普通模式为⽌，在此
期间输⼊或删除的任何内容都被当成⼀次修改（在此期间上下左右移动会打断）
- u: 撤销undo
- R: 重做redo

三、意外收获

偶然的发现vim的黑洞寄存器，默认的删除，选中等操作会将内容存入寄存器，有时候我们想要永久删除，则可以使用黑洞寄存器进行操作，"_d 替换 d，后面具体展开

### 问题

随着学到的指令越来越多，已初步可以在vscode中使用，但仍不熟练，还需加强联系，另外，发现vim的语法挺好理解，只要认识语法 + 操作（范围），就可以扩展开来，诸如 yank inner word(yiw)，yank inner phrase(yip)，等，diw，dip，viw，vip各种排列组合，越来越有趣了