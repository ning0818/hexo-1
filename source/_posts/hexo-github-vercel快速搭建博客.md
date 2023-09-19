---
abbrlink: ''
categories: []
date: '2023-02-10 15:34:40'
tags: []
title: hexo-github-vercel快速搭建博客
updated: Fri, 10 Feb 2023 07:34:40 GMT
---
# 1.安装node

[Download | Node.js (nodejs.org)](https://nodejs.org/en/download/)


![https://image.yuanning0818.tk/1676014539153.png](https://image.yuanning0818.tk/1676014539153.png)


安装git

[Git - Downloads (git-scm.com)](https://git-scm.com/download/)

安装fastgithub

[github超级加速 - 阳光下的小宁宁の博客 (yuanning0818.tk)](https://www.yuanning0818.tk/2022/12/08/github%E8%B6%85%E7%BA%A7%E5%8A%A0%E9%80%9F)


# 2.win+r输入cmd回车

输入`npm install hexo-cli -g`回车

![https://image.yuanning0818.tk/1676014593434.png](https://image.yuanning0818.tk/1676014593434.png)

![https://image.yuanning0818.tk/1676014716402.png](https://image.yuanning0818.tk/1676014716402.png)


# 3.安装好后，随便在哪里新建一个文件夹，cd进去

![https://image.yuanning0818.tk/1676014752180.png](https://image.yuanning0818.tk/1676014752180.png)


# 4.输入

```
hexo init
```

回车

# 5.去[Themes | Hexo](https://hexo.io/themes/)找一个喜欢的主题

进入，下载下来

解压复制到themes目录下，把名字前面的“hexo-theme-”去掉



6.去根目录的config.yml找到theme，改为你的主题名称，（不带hexo-theme-）比如volantis（一定不能少空格·）

![https://image.yuanning0818.tk/1676015213748.png](https://image.yuanning0818.tk/1676015213748.png)


好了，去[GitHub](https://github.com/)注册账号

之后如图操作

![https://image.yuanning0818.tk/1676015294961.png](https://image.yuanning0818.tk/1676015294961.png)


![https://image.yuanning0818.tk/1676015352379.png](https://image.yuanning0818.tk/1676015352379.png)

![https://image.yuanning0818.tk/1676015386962.png](https://image.yuanning0818.tk/1676015386962.png)


# 7.根目录下的所有文件上传到仓库

教程见[github快速上传文件夹[不需要任何软件] - 阳光下的小宁宁の博客 (yuanning0818.tk)](https://www.yuanning0818.tk/2023/01/28/github%E5%BF%AB%E9%80%9F%E4%B8%8A%E4%BC%A0%E6%96%87%E4%BB%B6%E5%A4%B9/)

![https://image.yuanning0818.tk/1676016150048.png](https://image.yuanning0818.tk/1676016150048.png)

![https://image.yuanning0818.tk/1676015501240.png](https://image.yuanning0818.tk/1676015501240.png)

# 8.去[vercel.com](https://vercel.com),用github登录

然后如图操作


![https://image.yuanning0818.tk/1676015592218.png](https://image.yuanning0818.tk/1676015592218.png)

点击黑色的什么什么github

找到刚才的仓库，import

![https://image.yuanning0818.tk/1676015704001.png](https://image.yuanning0818.tk/1676015704001.png)

![https://image.yuanning0818.tk/1676015803264.png](https://image.yuanning0818.tk/1676015803264.png)

过一会，满屏烟花部署成功后1

然后去你的域名商，添加解析，cname，vercel.cdn.cyfan.top

![https://image.yuanning0818.tk/1676015881647.png](https://image.yuanning0818.tk/1676015881647.png)


好了，进到vercel里你的项目，进入seetings》domains，输入你的域名，add

然后进入seetings》Functions

选择Hong Kong (East) – hkg1

![https://image.yuanning0818.tk/1676015989734.png](https://image.yuanning0818.tk/1676015989734.png)

好了，访问你的域名，就好啦

然后可以搭建后台，见[部署程序 | Qexo (oplog.cn)](https://www.oplog.cn/qexo/start/build.html)[注意，这是集成部署，不是本地部署！]
