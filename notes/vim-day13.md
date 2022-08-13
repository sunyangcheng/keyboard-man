### 收获&学习心得&心路历程

目标：掌握替换字符

1、替换命令 substitute

先用冒号进入命令模式

公式:[range]s[ubstitute]/{pattern}/{string}/[flags]

注意：按回车才会替换成功，不按不会替换

例如：:%s/vim/node 把vim改成node

- range
  - $ 到尾部
  - % 全局
  - number，number行
- flags
  - g 全文匹配 :%s/vim/node/g
  - c 提示框
- 可视化模式（确定范围）s/vim/node/

2、 多选操作

- bg （区分大小写） 多光标操作

### 问题

个人觉得，多选操作可以用vscode自带的ctrl + d代替（因为滚动屏幕少用），替换也可以用vscode的替换代替，毕竟vscode的操作简单，也比较好用。当然熟悉vim的替换也是不可或缺的，毕竟就是来学vim的，工作中服务器上可没有vscode用，练就完了。
