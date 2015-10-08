title: test asset folder
date: 2015-10-07 17:28:45
tags:
---
## 测试资源文件夹的使用 ##

添加图片，方法一：

> `![图1](/img/001.jpg)`

![图1](/img/001.jpg)

添加图片，方法二：

> `{% asset_img slug [图2] %}`

{% asset_img slug [图2] %}

不懂Hexo 3.0 中增加的几个插件，不知道如何使用。试试。

*The end.*

<p  id="test"> test pe </p>

  <script>
    var hname = location.hostname;
    if ( hname == "yzx.space" || hname == "www.yzx.space" )
    {
      document.getElementById("test").innerHTML= hname + "  if";
      //var _hmt = _hmt || [];
      //(function() {
       // var hm = document.createElement("script");
        //hm.src = "//hm.baidu.com/hm.js?1c0e50227b2b154aede8a69d70ccb4c2";
        //var s = document.getElementsByTagName("script")[0]; 
        //s.parentNode.insertBefore(hm, s);
      //})();
    }
    else // url = yzx.link  
    {
      document.getElementById("test").innerHTML= hname + "  else if";
      //var _hmt = _hmt || [];
      //(function() {
        //var hm = document.createElement("script");
        //hm.src = "//hm.baidu.com/hm.js?f6cf390bc4ae378d8bacfc01c4b0ef9a";
        //var s = document.getElementsByTagName("script")[0]; 
        //s.parentNode.insertBefore(hm, s);
      //})();
    }
  </script>
