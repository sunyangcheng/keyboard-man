### 收获&学习心得&心路历程：

目标：掌握悬浮显示&⼤⼩写&注释

1. 掌握悬浮显示

- `gh`: 类似鼠标移动到对应的变量上
- `esc`或`ctrl + [`退出悬浮显示

2. 大小写切换

    (1) normal mode

    - `gU`：大写操作，如`gUiw`将光标所在的单词大写
    - `gu`: 小写操作，同理上

    (2) visual mode

    - `U` 选中文字大写
    - `u` 选中文字小写

    (3) ~单个字符大小写切换

3. 注释

- `gc`: 单行注释
- `gC`: 多行注释
- `gcc`: 切换单行注释状态

光标在第一行，输入`gcl`或`gcc`, 即可注释掉该行

```js
import { calcHeight, getEl } from '@/utils';
```

光标移动到`getEl`上，输入`gCiw`即可只注释`getEl`, 如下：

```js
import { calcHeight, /* getEl */ } from '@/utils';
```

### 问题：
