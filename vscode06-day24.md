### 收获&学习心得&心路历程：

目标：掌握git

- leader g g: 打开source control面板
- leader g s: git add命令
- leader g c: git commit命令
- leader g p: git push命令
- leader g l: git log命令
- leader g d f: git diff命令
- leader g b: git branch命令
- leader g u: git pull命令

- 配置

```json
  {
    "before": ["<Leader>", "g", "c", "l"],
    "commands": ["git.clean"]
  },
  {
    "before": ["<Leader>", "g", "d", "f"],
    "commands": ["git.openChange"]
  },
  {
    "before": ["<Leader>", "g", "c"],
    "commands": ["git.commit"]
  },
  {
    "before": ["<Leader>", "g", "g"],
    "commands": ["workbench.view.scm"]
  },
  {
    "before": ["<Leader>", "g", "s"],
    "commands": ["git.stage"]
  },
  {
    "before": ["<Leader>", "g", "u"],
    "commands": ["git.unstage"]
  },
```

### 问题：

不怎么用这个插件，简单过一遍，主要是利用leader来实现按键的思想，这在windows上很友好