## AOSC OS 打包踩坑记录

https://wiki.aosc.io/zh/dev-sys-basics

### `ciel config -i stable` 时提示 `ciel-local.list` 不存在

问题：`un-initialize local repository remove stable/etc/apt/sources.list.d/ciel-local.list: no such file or directory`

解决：在执行这个命令的时候进入 `stable/etc/apt/sources.list.d` 创建一个 `ciel-local.list`。
