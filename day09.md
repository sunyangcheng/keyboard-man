### 收获&学习心得&心路历程：

目标：掌握更⾼效的移动-想去哪⾥就去哪⾥

一、更高效的移动

1. vim-easymotion

- <leader> <leader> w: Start of word forwards
- <leader> <leader> b: Start of word backwards
- <leader> <leader> e: End of word forwards
- <leader> <leader> ge: End of word backwards
- <leader> <leader> l: Matches beginning & ending of word, camelCase, after _, and after # forwards
- <leader> <leader> h: Matches beginning & ending of word, camelCase, after _, and after # backwards
- <leader> <leader> j: Start of line forwards
- <leader> <leader> k: Start of line backwards
- <leader> <leader> <leader> j: jumpToAnywhere motion;default behavior matches beginning & ending of word, camelCase, after _ and after #

2. vim-sneak

- 匹配s+2个字符
- 改键：
  - 替换原生的f功能
  - 利用映射来实现原有的s/S/z/Z
- v/normal + f + 2char
- operation + z + 2char

### 问题：

个人感觉vim-easymotion和vim-sneak更多的是锦上添花，实际用途并不广泛，完全可被原生的f,w,e,b,等搭配hjkl代替。