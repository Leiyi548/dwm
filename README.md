# dwm

## 快捷键

### 窗口

| 快捷键                  | 功能                             |
| ----------------------- | -------------------------------- |
| `super` + `ctrl` + `q`  | 关闭 dwm                         |
| `super` + `q`           | 关闭窗口                         |
| `alt` + `1-9`           | switch tag(1-9)                  |
| `alt` + `shift` + `1-9` | 将 application 带入对应 tag(1-9) |

### 布局

| 快捷键        | 功能            |
| ------------- | --------------- |
| `super` + `t` | `tile`布局 平铺 |
| `super` + `f` | `NULL`布局 浮动 |
| `super` + `m` | `monocle`布局   |

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
