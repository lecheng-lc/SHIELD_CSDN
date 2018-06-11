由于adsafe，屏蔽不了CSDN上的一些广告，比如这  
![广告](https://img-blog.csdn.net/20180611214904376?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yX1lhbllhbg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)  
再比如这个：  
![广告](https://img-blog.csdn.net/20180611211614155?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yX1lhbllhbg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)

----------

更可恶的是有时候这个广告上面给我来个“中出什么什么”，醉了醉了。下面就说说怎么在chrome浏览器中解决这个问题：
其实并不难，只需要这样一段简单的代码，把内嵌的iframe层去掉。
```js
for (var i = 0; i < document.getElementsByTagName("iframe").length; i++) {
    document.getElementsByTagName("iframe")[i].style.display = "none";
}
```
> 操作步骤

* [git 传送门下载](https://github.com/leChengWebDev/SHIELD_CSDN)
* 点击扩展程序，如下图
![扩展插件](https://img-blog.csdn.net/20180611214122601?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yX1lhbllhbg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
*加载以解压的扩展程序
![加载解压程序](https://img-blog.csdn.net/20180611214306119?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yX1lhbllhbg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
**<font color="blue">完成</font>**


----------


### 效果如下
![效果](https://img-blog.csdn.net/20180611215000156?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L01yX1lhbllhbg==/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70)
