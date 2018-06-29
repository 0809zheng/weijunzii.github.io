---
layout: post
title: 'jekyll-theme-H2O 配置 gitalk'
subtitle: '感谢'
date: 2018-06-29
author: 伪君子
categories: 技术，编程
cover: ''
tags:  网站 博客

---

* content
{:toc}


前提是 [搭建了博客](ttps://weijunzii.github.io/2018/04/02/Use-github-Set-Up-The-Blog.html)，使用的主题是 [jekyll-theme-H2O](https://github.com/kaeyleo/jekyll-theme-H2O/) 这个主题。其余的可以借鉴，但不一定完全适用。

#  0  注册 GitHub Application

首先要注册一下 GitHub Application，
>[https://github.com/settings/applications/new](https://github.com/settings/applications/new)

![](https://upload-images.jianshu.io/upload_images/2989110-4a0a03966f357a46.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
注册完就会有 Client ID 和 Client Secret

![](https://upload-images.jianshu.io/upload_images/2989110-c856407bdf2877b9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#  1  配置 ``_config.yml``

在 comments 那添加
```html
  gitalk: true
  gitalk_clientID: 'Client ID'
  gitalk_Secret: 'Client Secret'
  gitalk_repo: '用户名.github.io'
  gitalk_owner: '用户名'
  gitalk_admin: '用户名'
  distractionFreeMode: true
```
是在 comments 下面那添加，不要搞错地方。
![](https://upload-images.jianshu.io/upload_images/2989110-c27643270bc9d4a0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#  2  配置 ``post.html``
文件的位置在 ``_layouts\post.html``
##  2.0  在 ``<html>`` 这个标签下添加
在 ```<html>``` 这个标签下加上这两行
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.css">
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
```
就像这样
![](https://upload-images.jianshu.io/upload_images/2989110-84c51b2a8c713798.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

##   2.1  在``{% include footer.html %}``里添加
```html
<script src="https://cdn.jsdelivr.net/npm/gitalk@1/dist/gitalk.min.js"></script>
```
如图所示，位置不要搞错
![](https://upload-images.jianshu.io/upload_images/2989110-c10dd3d79b1efee4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
##  2.2  在``{% if site.comments.disqus %}``后面添加
```html
  {% if site.comments.gitalk %}
	<script>
		var gitalk = new Gitalk({
			  clientID: '{{ site.comments.gitalk_clientID }}',
			  clientSecret: '{{ site.comments.gitalk_Secret }}',
			  repo: '{{ site.comments.gitalk_repo }}',
			  owner: '{{ site.comments.gitalk_owner }}',
			  admin: '{{ site.comments.gitalk_admin }}',
			  id: location.pathname,      // Ensure uniqueness and length less than 50{{ page.title }}
			  distractionFreeMode: '{{ site.comments.distractionFreeMode }}'  // Facebook-like distraction free mode
			})

			gitalk.render('disqus_thread')
	</script>
  {% endif %}
```
如图所示
![](https://upload-images.jianshu.io/upload_images/2989110-1aebbf1abb854ebb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

关于 ``post.html`` 这部分的修改可以看一下我的[修改](https://github.com/weijunzii/weijunzii.github.io/commit/0ba47d4b3b437d73f7079bb9efba181f172520d7)

保存修改，再提交。

#  3  开 issues
进入博客，点击设置，
![](https://upload-images.jianshu.io/upload_images/2989110-e4091c3257e87b3e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
进去后勾选一下 issues 就搞定了。
![](https://upload-images.jianshu.io/upload_images/2989110-dedec6f428555672.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

再去看一下你博客里面的文章，如果说出现了评论框，那就是成功了。
![](https://upload-images.jianshu.io/upload_images/2989110-84fa2b8630072736.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#  4 相关说明

参考了这篇文章才实现的：[https://tea9.github.io/2018/06/24/gitali_config.html](https://tea9.github.io/2018/06/24/gitali_config.html)
文章作者写的说明：[http://note.youdao.com/publicshare/?id=6ea132ba501b49b2928125a694cc9ad9#/](http://note.youdao.com/publicshare/?id=6ea132ba501b49b2928125a694cc9ad9#/)

使用的主题是：[jekyll-theme-H2O](https://github.com/kaeyleo/jekyll-theme-H2O/) 

感谢两位作者~~