---
title: GitHub访问速度慢
author: 小枫叶
avatar: 'https://starlovei-1257629504.cos.ap-chengdu.myqcloud.com/Image/78468086_p0.png'
comments: true
tags:
  - 网络
date: 2020-03-03 15:33:11
categories: 转载
mathjax:
photos: https://starlovei-1257629504.cos.ap-chengdu.myqcloud.com/GitHub/pGbUR5AXI4_small.jpg
description: 半个月没更新博客都快忘了怎么写文章,果然还得不停练习
---
> **作者: 月正明 链接: https://zhuanlan.zhihu.com/p/93436925**

**ps:半个月没更新博客都快忘了怎么写文章,果然还得不停练习**
## 修改本地hosts文件
windows系统的hosts文件的位置如下：C:\Windows\System32\drivers\etc\hosts
mac/linux系统的hosts文件的位置如下：/etc/hosts
## 增加映射
获取Github相关网站的ip
访问[IPAddress](https://www.ipaddress.com), 拉下来, 找到页面中下方的“IP Address Tools – Quick Links”
分别输入github.global.ssl.fastly.net和github.com，查询ip地址
下面是我的配置
140.82.114.4	github.com
199.232.5.194	github.global.ssl.fastly.net
## .命令提示符中输入ping github.com
![logo](https://starlovei-1257629504.cos.ap-chengdu.myqcloud.com/GitHub/v2-995655f0ee75bb13fb1b602a9ad67201_r.jpg)
![logo](https://starlovei-1257629504.cos.ap-chengdu.myqcloud.com/GitHub/v2-df6267d10017a68eadb95c7c19bc251a_r.jpg)
再次访问流量器https://github.com, 秒出
![logo](https://starlovei-1257629504.cos.ap-chengdu.myqcloud.com/GitHub/v2-edc4eecb647a91a45f5bb012181f5d5f_r.jpg)