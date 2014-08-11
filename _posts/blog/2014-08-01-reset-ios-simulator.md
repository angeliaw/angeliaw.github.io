---
layout: post
title: 重置iOS simulator
category: blog
description: 
tags: iOS
---
2014-08-01 By {{ site.author_info }}
***
iOS 模拟器使用很长时间常出现各种错误，诸如无法输入，手势失灵等等，无论是开发还是测试都需要重置模拟器。常用的有两种方法

###使用脚本
```
tell application "iPhone Simulator"
	activate
end tell
tell application "System Events"
	tell process "iPhone Simulator"
		tell menu bar 1
			tell menu bar item "iOs Simulator"
				tell menu "iOs Simulator"
					click menu item "Reset Content and Settings…"
				end tell
			end tell
		end tell
		tell window 1
			click button "Reset"
		end tell
	end tell
end tell
```

###iOS模拟器设置中的重置功能，见下图
![reset ios simulator](/images/blog/resetiossimulator.png)


[Angelia]:    http://angeliaw.github.com  "Angelia"
