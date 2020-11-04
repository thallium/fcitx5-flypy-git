# fcitx5-flypy
小鹤音形 aka xhyu or flypy for fcitx5

## Installation
Arch Linux:

`yay fcitx5-flypy-git`

Manual build:

`sudo makepkg -sfi`

## Use you own customized table
1. modify flypy.txt
2. recompile table using `libime_tabledict flypy.txt flypy.dict`
3. reinstall using `sudo makepkg -sfi`
