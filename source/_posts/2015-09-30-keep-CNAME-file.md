title: keep CNAME file
date: 2015-09-30 22:02:20
tags:
---
在Github Page 上绑定自定义的域名，需要在repo的根目录添加CNAME文件。

根据github上的帮助文件，在线完成添加CNAME文件的操作，测试可用。

但是，每次hexo部署之后会自动删除CNAME文件，导致绑定失效。

问题来了，如何保留这个CNAME文件呢？


通过搜索，在知乎上看到解决方案，测试可行。

方法是：直接将CNAME文件添加到 'hexo init' 命令生成的目录下的source目录中，重新部署之后，就可以将CNAME文件上传到repo的跟目录中。同理，README.md文件也可以通过此方法上传。

[知乎网址](http://www.zhihu.com/question/28814437)
