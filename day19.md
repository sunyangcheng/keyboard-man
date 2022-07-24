### 收获&学习心得&心路历程：

目标：操作文件

1. 切换`files explorer`区域 资源管理器区域
    vscode：默认命令 `ctrl + shift + e`，改成命令 ctrl + ;
    ```json
    // keybindings.json
    {
      "key": "ctrl+;",
      "command": "workbench.view.explorer",
      "when": "viewContainer.workbench.view.explorer.enabled"
    }
    ```

2. 切换到编辑区
    vscode：默认命令 `shift + alt + 1`，改成命令 `ctrl + '`
    ```json
    // keybindings.json
    {
      "key": "ctrl+'",
      "command": "workbench.action.moveEditorToFirstGroup"
    }
    ```

3. 移动光标 jk
4. 展开/折叠 h/l 
  当是文件时，按l 打开文件

5. 创建文件
    
  - 在 `files explorer` 中： `a`

    ```json
    // keybindings.json
    {
      "key": "a",
      "command": "explorer.newFile",
      "when": "filesExplorerFocus && !inputFocus"
    },
    ```
  - 在 `editor` 中：`space + n + f`
    
    ```json
    // settings.json
    "vim.normalModeKeyBindingsNonRecursive": [
      // 新建文件
      {
        "before":["<Leader>", "n", "f"],
        "commands":["explorer.newFile"]
      }
    ]
    ```
  - vscode : `ctrl + n`

  - 使用插件 `file utils`

6. 创建文件夹

  - 在 `files explorer` 中：`A`

    ```json
    // keybindings.json
    {
      "key": "shift+a",
      "command": "explorer.newFolder",
      "when": "filesExplorerFocus && !inputFocus"
    },
    ```

  - 在`editor`中：`space + n + f`
    
    ```json
    // settings.json
    "vim.normalModeKeyBindingsNonRecursive": [
      // 新建文件夹
      {
          "before":["<Leader>", "n", "d"],
          "commands":["explorer.newFolder"]
      }
    ]
    ```

  - 使用插件 `file utils`

问题：
xxxxxxx