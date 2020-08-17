# 在GitHub上搭建静态博客

## 1. 准备申请域名

可以在网上查一查帖子有很多。

主要格式：username 是你的GitHub的账户名称，但是需要注意一点，这个需要和你的本地的gitbash的名字相同，不相同的话可能显示不全。（最好本地和远端是相同)

```
username.github.io
```

## 2. 选择自己喜欢的博客模板

我选择的博客模板是这位大佬：

```
https://github.com/huxpro/huxpro.github.io
```

需要克隆到自己的本地文件，修改配置文件，但是在readme当中需要把Friend函数当中的内容注释掉，因为GitHub一直在爆错误，没有去查。但是我使用格式检查工具，检查到是格式有问题，但是我看编写代码的格式是正确的，没有错误，不知道为什么。

## 3. 配置config.yml文件

```javascript
# Site settings
title: 天唐锦绣
SEOTitle: 天唐锦绣 博客 | bitromance Blog
header-img: img/home-bg.jpg
email: 1093965574@qq.com
description: ""
keyword: ""
url: "https://bitromance.github.io"              # your host, for absolute URL
baseurl: ""         # for example, '/blog' if your blog hosted on 'host/blog'



# SNS settings
RSS: false
weibo_username:     孤单行人
zhihu_username:     孤单行人
github_username:    bitromance
#twitter_username:  huxpro
#facebook_username:  

```

主要修改文件的title等，但是现在面临一个问题，就是不能上传图片。

也不是不能上传图片，只是在html镜面并不能显示我上传的图片，但是上传网络图片可能依赖网速把。但是我自己上传的图片并不能显示，这是一个很严重的问题。

## 4. 编写第一篇博客
随便编一个blog上传就可以了，但是需要注意上传文件的名字格式。这个是很严格。
大概格式是：
```
year-month-days-what-blog.md
```