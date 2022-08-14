# dwm

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

### 布局

| 快捷键                      | 功能              |
| --------------------------- | ----------------- |
| `super` + `t`               | `tile`布局 平铺   |
| `super` + `f`               | `NULL`布局 浮动   |
| `super` + `m`               | `monocle`布局     |
| `super` + `shift` + `space` | toggle float mode |

### 鼠标

| 快捷键                          | 功能                     |
| ------------------------------- | ------------------------ |
| `leftmouseclick` + `tag`        | 将当前窗口移动到对应 tag |
| `rightmouseclick` + `clientwin` | resize window            |
| `midmouseclick` + `clientwin`   | toggle float            |

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
