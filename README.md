# dwm

## 安装

[dwm-官网](https://dwm.suckless.org/)

安装好的 dwm 是一个 tar.gz，我们需要解压缩它。然后修改名字。

```sh
tar -zxvf dwm-6.3.tar.gz . && mv dwm-6.3 dwm
```

## 快捷键

### 窗口

| 快捷键                  | 功能                             |
| ----------------------- | -------------------------------- |
| `super` + `ctrl` + `q`  | 关闭 dwm                         |
| `super` + `q`           | 关闭窗口                         |
| `alt` + `1-9`           | switch tag(1-9)                  |
| `alt` + `shift` + `1-9` | 将 application 带入对应 tag(1-9) |
| `alt` + `tab`           | switch recent tag                |
| `super` + `` ` ``       | scratchpad st                    |
| `super` + `1-9`         | toggle 那个标签的页面()          |

### 布局

| 快捷键                      | 功能              |
| --------------------------- | ----------------- |
| `super` + `t`               | `tile`布局 平铺   |
| `super` + `f`               | `NULL`布局 浮动   |
| `super` + `m`               | `monocle`布局     |
| `super` + `shift` + `space` | toggle float mode |

### 鼠标

| 快捷键                                        | 功能                     |
| --------------------------------------------- | ------------------------ |
| `leftmouseclick` + `super` + `tag`            | 将当前窗口移动到对应 tag |
| `rightmouseclick` + `clientwin(当前应用窗口)` | resize window            |
| `midmouseclick` + `clientwin(当前应用窗口)`   | toggle float             |
| `rightmouseclick` + `tagbar(标签页)`          | toggle 对应标签的页面    |
| `leftmouseclick` + `titlebar(标题栏)`         | 切换为 monocle 布局      |
| `midmouseclick` + `titlebar(标题栏)`          | 关闭这个窗口             |
| `rightmouseclick` + `titlebar(标题栏)`        | zoom                     |
| `leftmouseclick` + `symbol(布局切换)`         | 切换最近布局             |
| `midmouseclick` + `symbol(布局切换)`          | 切换 monocle 布局        |
| `rightmouseclick` + `symbol(布局切换)`        | 切换 tile 布局           |

## add patch

### example

`hide_vacant_tags`

```sh
mdkir patch && cd patch
wget https://dwm.suckless.org/patches/hide_vacant_tags/dwm-hide_vacant_tags-6.3.diff
cd ..
patch -p1 < patch/dwm-hide_vacant_tags-6.3.diff
```

## patches

- [hide vacant tags
  ](https://dwm.suckless.org/patches/hide_vacant_tags/)
- [fullgaps
  ](https://dwm.suckless.org/patches/hide_vacant_tags/dwm-hide_vacant_tags-6.3.diff)
- [scratchpad](https://dwm.suckless.org/patches/scratchpad/)
- [cyclelayouts](https://dwm.suckless.org/patches/cyclelayouts/)
- [autostart](https://dwm.suckless.org/patches/autostart/)
- [viewontag](https://dwm.suckless.org/patches/viewontag/)
- [fancybar](https://dwm.suckless.org/patches/fancybar/)
- [alpha](https://dwm.suckless.org/patches/alpha/)
- [systray](https://dwm.suckless.org/patches/systray/) 
