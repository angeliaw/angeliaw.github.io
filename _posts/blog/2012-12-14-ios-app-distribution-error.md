---
layout: post
title: app发布validate错误修正
category: blog
description: 
---
###问题:
利用Xcode Analyze时出现错误:this bundle is invalid. the application-identifier entitlement is not formatted correctly.... （见图1）

![chart 1](/images/blog/13554960286552.png)
>利用Xcode可以静态分析代码，检查代码的潜在内存泄露； 

###解决办法：

在appname.entitlements中添加application-identifier 并赋值（见图2），然后重新Analyze，就不会再有错误提示了

![chart 2](/images/blog/13554962363888.png)

[Angelia]:    http://angeliaw.github.com  "Angelia"



