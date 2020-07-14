---
layout: article
title: 零成本创建一个可以盈利高质量的niche站
key: 10002
tags: niche站
date: 2020-07-14
---

本文教大家以`零成本`的方式来创建一个可盈利的`niche站`，对，`零成本`。

大多数地方教大家开始建站的时候，第一步都是先从Bluehost、Vultr或者阿里云等服务商购买服务器。不论是国内还是国外的服务器每个月至少都需要几十上百刀花费。但这种方法却可以让你完全免掉这个费用，并且创建一个访问性能优异的站点。

这个方法便是通过 `Github Pages`来建立一个专业的站点。

![github-pages](https://res.cloudinary.com/dciv8ebqh/image/upload/v1594622115/github-pages_qix6bs.png)

如果对编程有了解，一定会知道`Github`这个网站，世界最著名的开源站点，对程序员来说是最重要的一个网站。

`github`不仅可以托管开源项目，它还有个特别实用的功能便是`github pages`，也就是创建一个`静态网站`。

### 什么是静态网站？

`静态网站`是相对于`动态网站`而来的，它不需要数据库的支持，直接通过`jekyll`或者`hexo`等系统生成可以直接访问的`html`页面。

静态站点可以像`Wordpress`一样托管在自己的服务器上，但它也可以直接部署在`github`上面。

**github pages 的优点**

* 访问的是html页面，没有数据库访问过程，速度更快
* 更安全（因为本身是静态页面，完全没有攻击入口）
* 依托`git`版本记录工具，自带版本记录功能
* 更有利于SEO
* 免费
* 使用`markdown`标记语言写内容，简单方便（对于某些人来说，也是缺点）
* 可以使用github的二级域名，也可以使用自己购买的域名

**github pages的缺点**

* 有一定的门槛，需要学习一些简单知识
* 没有数据库支持，所有内容都可以被人公开看到
* 没有Wordpress那样强大的插件支持
* 主题设置相对复杂
* 图片比较麻烦
* 评论需要使用三方的

### GitHub Pages 站点设置

`github`每个账号可以设置一个`GitHub pages`，所以如果想用github来建立多个站点的话，需要申请多个github 账号。好在GitHub账号申请的门槛很低，只需要有个邮箱便可以申请，并没有什么特别的限制。

GitHub Pages 站点目前的限制是:

* 站点容量不得大于1GB

* 每月流量限制为100GB

* 每小时提交次数不得超过10次。

这个限制对于一般站点来说完全够用了。站点主要保存的都是`md`文档，基本上不占用什么空间。运营过网站都知道100GB是个什么概念，能到这个时候说明站点已经到了一定程度了。至于每小时提交不超过10次，这个更没什么好担心的。

下面简单几步我们便可以创建属于自己的github pages站点。

#### #1. 注册github账号

打开github官网 ： https://github.com/ 

如下图所示：

![github-account-register](https://res.cloudinary.com/dciv8ebqh/image/upload/v1594621371/github-register_kmilfa.png)

直接在首页输入`用户名`、`邮箱`和`密码`。这个用户即`username`需要在github站点上唯一的，可能需要多尝试几个。邮箱需要填写真实的邮箱，因为后面需要验证邮箱，再设置好密码一定要记住。完成之后点击`Sign up for Github`。

{:.warning}

注册填写用户名的时候这里需要注意，如果使用github提供的二级域名的话，它的格式为` https://<username>.github.io` 。其链接中的 `<username>`必须为你注册时候填写的用户名。所以，如果你不绑定自己购买的域名的话，这里可以注册的时候便设置为你站点相关的名称，会看起来更舒服一些。

### #2. 设置github pages

接下来只需要按照指定格式创建一个新的`Reponsitory`即可。

首先登录自己上面注册的github账号，然后点击右上角的➕号，点击 `New Reponsitory`。如下图所示：

![github-new](https://res.cloudinary.com/dciv8ebqh/image/upload/v1594726515/github-new-reponsitory_jsq3sx.png)

接下来，会出现创建新Repository所需填写的信息

![](https://res.cloudinary.com/dciv8ebqh/image/upload/v1594726633/create-new-reponsitory_ymwa7k.png)



`Repository name`必须按照规定的格式来填写，如上我的Github用户名为**affiliate-site**，则Repository name为**affiliate-site.github.io**，是否公开选择**Public**，接下来勾选 **Initialize this repository with a README**。

一切完成后，点击**Create repository**。

完成以后，便可以使用 https://affiliate-site.github.io来访问刚创建的站点了。

GitHub pages 还有很多复杂的玩法，比如找到更好功能更多的主题，添加更加复杂的 功能，还可以把自己的域名指定到站点上，这样，和其他方式创建的网站看起来就没有什么区别了。

### 总结

Github pages站点如果可以使用熟练，可以给自己省一大笔费用。它对谷歌的seo做的很好，目前百度不能直接收录github pages页面，因为GitHub主动屏蔽了百度爬虫的抓取，但是有其他办法可以解决这个问题。

即使不使用cdn，github pages对很多国家的速度也非常不错，如果想要，也可以使用cdn来加速。

Github pages可以说定制程度非常高，自身也有很多优良的插件可以使用。当然，这需要我们有一定探索的能力。如果对此有兴趣的朋友可以尝试。