###  收获&学习心得&心路历程：

1. 新增宏：

- 录制：q+宏名称(以下称为a) 开始录制宏操作 按 `q` 结束录制
- 查看：:reg a
- 使用：
  - @a：执行一次宏操作
  - @@：执行最近一次的宏操作
  - 搭配数字，完成多次宏操作，如 10@a
  - 技巧：利用宏的安全机制，将数字变大，执行不了则自动结束，如1000@a

2. 修改宏：(vscode用不了)

- 追加：q+大写宏名称(qA)
- 修改："ap 取出宏，修改后，"ayy进行保存

### 问题：

目前感觉宏的功能很强大，但是在工作中可能使用的不是特别多，没能想到什么场景，gb应该可以处理大部分场景了。
