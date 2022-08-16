# 搜索與提問

[https://xyproblem.info/](https://xyproblem.info/)

![](../.gitbook/assets/image.png)

&#x20;

#### &#x20;垂直搜索   内容出现在哪？ 对应平台搜。

关键词  精准&#x20;

#### 搜索学习资源

明确学习资源，比如：课程叫什么  哪个平台的，哪个讲师。

到网盘搜 - **咸鱼搜 -** 看咸鱼里的商品截图的百度网盘资源的文件夹名字叫什么，或者文件名叫什么，然后再去网盘搜索网站搜索**，**当然如果实在搜不到，就直接咸鱼买了

一些语法搜索

#### 完全匹配搜索：""

&#x20;精准搜索。

```markup
"imyshare"
```

#### 搜索指定网站的内容：site

这个就很常用了，仅搜索某个网站的内容（当然这个网站的内容得被搜索引擎收录才行，否则搜不到），比如搜索imyshare网站的内容。

```markup
神器 site:imyshare.com
```

#### 搜索结果中必须包含某个关键字：+

可排除，当然可必须包含啦，比如我们搜索某个电影，里面必须要包含豆瓣。

```markup
我不是药神 +豆瓣
```

#### filetype:pdf  搜文件 书籍

```markup
断舍离 filetype:pdf
```

#### 搜索的关键字包含在网页内容文本中：intext，allintext

用法基本和inurl，allinurl一致，如果是多个关键词的话，用allintext。

```markup
allintext:pandownload 替代
```

#### 搜索的关键字包含在网页内容的锚链接中：inanchor

用法基本和inurl，allinurl一致，如果是多个关键词的话，用inanchor。

```markup
inanchor:网盘搜索大全
```

#### 搜索目录：index of

相当于搜索的是一个文件夹结构的内容，比如我想搜索哪些网站中存有movie，就可以得到下面这种FTP类似的结果啦，可以直接下载哦！

```markup
index of /movie
```

#### 搜索的关键字包含在网页标题中：intitle，allintitle

用法基本和inurl，allinurl一致，如果是多个关键词的话，用allintitle。

```markup
intitle:pandownload替代方案，百度网盘不限速下载
```

#### 搜索的关键字包含在链接中： inurl，allinurl

意思是搜索的关键词是包含在链接中的，而不是网站内容中。如果是多个的话，用allinurl。

```markup
reward -inurl
```

####

#### 排除部分内容：-

```markup
搜索技巧 -CSDN
```
