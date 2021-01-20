# fcitx5-flypy

小鹤音形 aka xhyx or flypy for fcitx5

## Installation

Arch Linux:

​	AUR:  `yay fcitx5-flypy-git`

​	Manual build: `sudo makepkg -sfi`

Others:

```bash
cp flypy.conf /usr/share/fcitx5/inputmethod/flypy.conf
cp flypy.dict /usr/share/libime/flypy.dict
```

## Use you own customized table

1. modify flypy.txt
2. recompile table using `libime_tabledict flypy.txt flypy.dict`
3. reinstall 
