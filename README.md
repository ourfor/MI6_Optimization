# MI6_Optimization
MI6调教指南

# 前言
不少同学觉得官方miui自定义不够强，纷纷刷官改和类原生。当然不少人喜欢原生系统，它纯净省电、可玩性极强，同时资源丰富，诸如` Xposed `等神器支持良好。不过，缺点也很明显，像***NFC***这些功能基本残废。bug还是有一些的，不影响日用。由于我对云服务很强，需要一个稳定省电的系统。所以本指南将以最新官方稳定系统为基础进行调教。除了安装第三方recovery以外，不会改动系统分区，从而最大程度保证系统的稳定和省电

> 一个稳定的系统可以极大的提高学习的效率       ---- ***鲁迅***
~~~帮我压好鲁迅的棺材盖😳🤪~~~
--- 
![bg-camera-small.jpg](https://i.loli.net/2018/08/15/5b7435e9a260b.jpg)
<div align=center><a>宣传图片</a></div>    

--- 
![bg-top-small.jpg](https://i.loli.net/2018/08/15/5b7435e988976.jpg)
<div align=center><a>梦幻般的四曲面</a></div>    

--- 
![bg-perfor-small.jpg](https://i.loli.net/2018/08/15/5b7435e98718a.jpg)
<div align=center><a>骁龙835</a></div>    

--- 
<a>
<div align=left><img src="https://i.loli.net/2018/08/15/5b7435e9266eb.jpg"></div>
<div align=right><img src="https://i.loli.net/2018/08/15/5b7435e9266eb.jpg"></div>
</a>

> 本指南将在官方MIUI的系统基础上对MI 6进行个性化，以达到稳定省电的目的。


So,不修改系统才能保证原来的稳定，所以这里使用Magisk模块(一部分自制，一部分来自酷友)：

- 什么是` Magisk `：   
Magisk是一款不修改系统文件但是能做到与修改系统相同效果的神器。  
[Magisk项目地址](https://github.com/topjohnwu/Magisk)

# 个性化Magisk模块
- 时间居中模块 miui_center_clocker
- MIUI主题（整合安卓7.0开机画面）
- 全面屏手势（包含禁用系统升级，Google相机代码）
- mm管理器（方便recovery下面卸载模块）
