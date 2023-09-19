---
abbrlink: 19972
categories:
  - - replit
  - - artalk
date: '2023-06-21 17:34:17'
tags:
  - replit
  - artalk
title: 使用replit搭建artalk后端
updated: 'Wed, 21 Jun 2023 09:34:45 GMT'
ai: >-
  这篇文章介绍了如何在replit.com上注册账号并使用GitHub连接,还提供了一系列步骤和截图，教你如何在replit上设置artalk后端。这个artalk后端提供了一个评论系统，让用户可以轻松在网站上进行评论。文章还提供了一些修改设置的说明，以及如何获取后端地址的指导。
---
#### 1.前往[https://replit.com/](https://replit.com/)注册账号（推荐用github）

#### 2. 依次点击


![https://image.yuanning0818.tk/1687340309986.png](https://image.yuanning0818.tk/1687340309986.png)

#### 3.打开shell，右键粘贴以下命令,回车

```shell
git clone https://github.com/ning0818/artalk-replit && mv -b artalk-replit/* ./ && mv -b artalk-replit/.[^.]* ./ && rm -rf *~ && rm -rf artalk-replit
```

![https://image.yuanning0818.tk/1687340901678.png](https://image.yuanning0818.tk/1687340901678.png)

#### 4.当shell输出

```shell
Cloning into 'artalk-replit'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 9 (delta 1), reused 7 (delta 0), pack-reused 0
Receiving objects: 100% (9/9), 33.33 KiB | 3.33 MiB/s, done.
Resolving deltas: 100% (1/1), done.
Detected change in environment, reloading shell...
```

时，点击上面的run

![https://image.yuanning0818.tk/1687341043638.png](https://image.yuanning0818.tk/1687341043638.png)

#### 5.打开artalk-go.yml，你要修改的：

![https://image.yuanning0818.tk/1687341200609.png](https://image.yuanning0818.tk/1687341200609.png)

注：密码需加密，推荐https://cmd5.com

#### 6.这就是你的后端地址

![https://image.yuanning0818.tk/1687341412558.png](https://image.yuanning0818.tk/1687341412558.png)

#### 7.之后的我就不说了，参考官方文档[👋 Hello Friend | Artalk](https://artalk.js.org/guide/intro.html)
