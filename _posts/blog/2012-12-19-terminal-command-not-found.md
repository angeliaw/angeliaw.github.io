---
layout: post
title: Terminal出现command not found
category: blog
description: 
tags: [mac, terminal]
---

###问题：
在Mac上，修改了.bash_profile文件后，因为填写错误，导致回到Terminal除了cd命令，其它命令都提示”command not found“

```
myMac:bin mac$ TOUCH
-bash: TOUCH: command not found
myMac:bin mac$ cd /usr/local/bin
myMac:bin mac$ touch
-bash: touch: command not found
```

###原因：
*/usr/bin:/bin:/usr/sbin:/sbin:/usr/local/bin:* 被从环境变量中删除了。
<br/>不能用 **PATH=/some/directory**，这样导致的结果是删除了*$PATH*中其他所有目录,必须添加 **PATH=/some/directory:$PATH；**

###解决办法：
将/usr/bin:/bin:/usr/sbin:/sbin:/usr/local/bin:再加入到环境变量。

```
myMac:~ mac$ export PATH="usr/bin:/bin:/usr/sbin:/sbin:/usr/local/bin:$PATH"
myMac:~ mac$ $PATH
```


[Angelia]:    http://angeliaw.github.com  "Angelia"
