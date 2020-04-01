# 百度网盘视频倍速播放

此脚本基于 Tampermonkey，使用需先安装 Tampermonkey

安装 Tampermonkey  [**Tampermonkey**](https://www.tampermonkey.net/)

安装脚本  [**Greasy Fork**](https://greasyfork.org/zh-CN/scripts/399131-百度网盘视频倍速)

---------

可以自由调整浏览器中百度网盘在线播放视频的倍速

安装完成后，在**视频加载完成后**会在屏幕右侧出现一个**蓝色圆圈** <div style="width:25px;height:25px;border-radius:13px;background-color:rgba(0, 70, 128, 0.1);border:1px solid rgba(0, 70, 128, 0.12);font-size:13px;color:rgba(0, 70, 128, 0.3);display:inline-block;text-align:center;">及</div> ，**鼠标悬浮**后出现菜单可自由调整视频播放的倍速

滑块的范围设置在 0.5 到 2.5，输入框上下按钮范围设置在 0 到 4，实际可以随意输入数字 1.75，~~10，100~~ 之类（实测太大也不会飞快，太小会直接暂停）

内置按钮设置了**x1**、**x1.5**、**x2**三种常用速度可快捷调整

每次打开视频可以读取上次设置的速度并自动调整

有问题欢迎 [**反馈**](https://github.com/E6ther/BaiduPan-VideoRate/issues)



## 相关说明

1. 只能对自己网盘中视频设置倍速，暂时无法对分享的视频倍速播放
2. 控制按钮位置设置在右侧距顶部 10% 的位置，暂时无法移动（~~能用就行~~）
