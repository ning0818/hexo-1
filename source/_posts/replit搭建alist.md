---
abbrlink: ''
categories: []
date: '2023-06-30T15:25:13.811213+08:00'
excerpt:  由于alist被replit封禁无法搭建，所以我参考网上各种文章，可算建好了。但是，太《麻烦》了。所以，我整理整理，  replit注册账号（推荐github登录）新建项目，语言为Blank Replit  将以下代码粘贴至Replit Shell后回车 rm -rf .replit &amp;&amp; git clone https://github.com/ning0818/alist-r...
tags: []
title: 使用replit搭建alist
updated: 2023-6-30T18:25:47.668+8:0
---
> `由于alist被replit封禁无法搭建，所以搭建困难，所以我参考网上各类资料后简化了搭建方法，快来试试吧！`

[replit](https://replit.com)注册账号（推荐github登录）新建项目，语言为Blank Replit
![image](https://github.com/ning0818/alist-replit/assets/117955401/d20159a2-cb34-4a9b-971f-d6824bbf22cc)

将以下代码粘贴至Replit Shell后回车

```shell
rm -rf .replit && git clone https://github.com/ning0818/alist-replit && rm -rf alist-replit/README.md && mv -b alist-replit/* ./ && mv -b alist-replit/.[^.]* ./ && rm -rf *~ && rm -rf alist-replit && tar -zxvf linux-amd64.tar.gz && rm -rf linux-amd64.tar.gz && rm -rf README.md && ./alist admin
```

当输出了密码时，记住密码，然后点击上面绿色的“run”

![image](https://github.com/ning0818/alist-replit/assets/117955401/ed968420-e259-4996-bed4-ddfaab1fbc32)

复制你的域名，访问
![image](https://github.com/ning0818/alist-replit/assets/117955401/a2b0ada6-7c0a-41b6-abb8-c5e182db8d5b)

输入记下的用户名密码，登录
![image](https://github.com/ning0818/alist-replit/assets/117955401/f5db5953-a089-437a-8170-8189834b4eaa)

之后添加存储修改密码什么的参见[官方文档](https://alist.nn.ci/zh/)
