title: 修改Ubuntu系统环境变量PATH
tail: P2
date: 2016-04-22 21:47:04
tags:
- linux
- ubuntu
- PATH
- bash
---

在linux系统中，如果安装了新的软件包，或者需要添加自定义的命令目录，可能需要手动修改环境变量 `$PATH`。


在 Ubuntu 中修改文件 `~/.bashrc`，在文件中添加如下命令即可：


```
# set PATH so it includes other bins if it exists
if [ -d "$HOME/custom/bin/" ] ; then
    PATH="$HOME/custom/bin/:$PATH"
fi
```

[ The end ]
