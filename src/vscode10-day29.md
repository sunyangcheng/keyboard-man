### 收获&学习心得&心路历程：

目标：掌握 vscode 终端

- ctrl + `: toggle终端
- ctrl + `\`: 终端分屏
- 清空终端：cls
- 分屏切换:
  - workbench.action.terminal.focusNextPane: ctrl + ]
  - workbench.action.terminal.focusPreviousPane: ctrl + [
- 关闭
  - workbench.action.terminal.kill: shift + alt + q
- 新建
  - workbench.action.: shift + alt + n
- 新建后，多个终端的切换（注意和分屏的切换不同）
  - workbench.action.terminal.focusPrevious: ctrl + shift + [
  - workbench.action.terminal.focusNext: ctrl + shift + ]

### 问题：

通过阅读源码，配置默认终端

- "terminal.external.windowsExec": "C:\\Users\\faisco\\AppData\\Local\\Microsoft\\WindowsApps\\wt.exe",