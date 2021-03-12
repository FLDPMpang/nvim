文档还在完善中...

# My neovim config files

[Colemak](https://colemak.com/) 用户使用的 [NeoVim](https://neovim.io) 配置文件

## 基础键位

| 快捷键     | 行为                             |
| ---------- | -------------------------------- |
| `[<SPACE>` | 向上新建一空行                   |
| `]<SPACE>` | 向下新建一空行                   |
| `N`        | 行首                             |
| `I`        | 行未                             |
| `-`        | 向上查找                         |
| `=`        | 向下查找                         |
| `Ctrl` `a` | 将光标移至当前行的末尾           |
| `Ctrl` `u` | 将光标所在的字母移至当前行的末尾 |

## 窗口管理

### 通过分裂屏幕创造窗口

| 快捷键      | 行为                                   |
| ----------- | -------------------------------------- |
| `s` `u`     | 新建一个分屏并把它放置在当前窗口的上面 |
| `s` `e`     | 新建一个分屏并把它放置在当前窗口的下面 |
| `s` `n`     | 新建一个分屏并把它放置在当前窗口的左边 |
| `s` `i`     | 新建一个分屏并把它放置在当前窗口的右边 |
| `s` `v`     | 将两个分屏垂直放置                     |
| `s` `h`     | 将两个分屏水平放置                     |
| `s` `r` `v` | 将所有分屏垂直放置                     |
| `s` `r` `h` | 将所有分屏水平放置                     |

### 切换不同的窗口

| 快捷键        | 行为           |
| ------------- | -------------- |
| `SPACE` + `w` | 移至下一个窗口 |
| `SPACE` + `n` | 移至左边的窗口 |
| `SPACE` + `i` | 移至右边的窗口 |
| `SPACE` + `u` | 移至上面的窗口 |
| `SPACE` + `e` | 移至下面的窗口 |

### 为不同的窗口调整大小

用方向键更改当前窗口的大小

### 关闭窗口

| 快捷键      | 行为                                                        |
| ----------- | ----------------------------------------------------------- |
| `Q`         | 关闭当前窗口                                                |
| `SPACE` `q` | 关闭当前窗口下面的窗口 (如果下面没有窗口，则当前窗口将关闭) |

### 标签页管理

| 快捷键      | 行为                     |
| ----------- | ------------------------ |
| `t` `u`     | 新建一个标签页           |
| `t` `n`     | 移至左侧标签页           |
| `t` `i`     | 移至右侧标签页           |
| `t` `m` `n` | 将当前标签页向左移动一格 |
| `t` `m` `i` | 将当前标签页向右移动一格 |

## 插件

### [coc.nvim](https://github.com/neoclide/coc.nvim)

| 快捷键      | 行为             |
| ----------- | ---------------- |
| `gd`        | 列出定义列表     |
| `gr`        | 列出参考列表     |
| `gi`        | 待办事项清单     |
| `gy`        | 转至类型定义     |
| `<LEADER>-` | 移动到上一个报错 |
| `<LEADER>=` | 移动到下一个报错 |
| `<LEADER>h` | 显示文档         |
| `ts`        | 翻译单词         |

### [coc.explorer](https://github.com/weirongxu/coc-explorer)

| 快捷键 | 行为           |
| ------ | -------------- |
| `tt`   | 打开文件浏览器 |
| `?`    | 帮助           |
| `i`    | 打开           |
| `o`    | 展开文件夹     |
| `a`    | 添加文件       |
| `yn`   | 复制文件名     |
| `M`    | 添加文件夹     |
| `cw`   | 重命名文件     |
| `.`    | 隐藏文件显示   |
| `b`    | 跳转到缓冲区   |

### [rnvimr](https://github.com/kevinhwang91/rnvimr)

| 快捷键   | 行为                 |
| -------- | -------------------- |
| `Ctrl+t` | 在新标签页中打开文件 |
| `Ctrl+x` | 上下分裂打开当前文件 |
| `Ctrl+v` | 左右分裂打开所选文件 |
