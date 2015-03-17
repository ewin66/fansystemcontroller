## 常见问题FAQ ##

1.智能实时散热系统是什么?

智能实时散热系统是由GIIT 09级部分学生所设计的用于笔记本智能散热的一个散热系统。这里公开源代码的部分是用于与智能实时散热系统的相关硬件进行通讯和控制的控制程序。通过控制程序，你可以方便的对硬件进行控制和信息同步。当然即使不连接硬件，控制程序也是一款优秀的系统实用程序。

2.智能实时散热系统能在那些操作系统上运行？

智能实时散热系统能在Windows XP(SP3)/Vista/7/8 操作系统上运行。如果你的操作系统是Windows Server系列，则不能保证一定能够正常运行。暂不能在Windows RT系统上运行。

3.为什么不能获取到CPU温度?

系统目前只能支持下列CPU，请确保您的CPU在支持列表中：
> AMD:
  * FX系列
  * APU系列
  * Phenom/Phenom II系列
  * Athlon II系列
  * Turion II系列
  * Athlon64系列
  * Athlon64 X2系列
  * Athlon64 FX系列
  * Turion64系列
  * Turion64 X2系列
  * 基于K8和K105的Sempron系列
  * 基于K8的单核心Opterons starting SH-C0和更新版本
  * 基于K8的双核心Opteron系列
  * 基于K10的四核心Opteron系列
  * 基于K10.5的八核心Opteron系列
  * 基于K10.5的十二核心Opteron系列
> Intel:
  * 酷睿i3, i5, i7 全系列
  * 凌动系列.
  * 酷睿单核系列
  * 酷睿双核系列
  * 酷睿2 Duo 系列
  * 酷睿2 Quad 系列
  * 酷睿2 Extreme 系列
  * 赛扬M400和500系列
  * 赛扬E1000和E3000系列
  * 奔腾E2000, E2100, E2200, E5000, E6000 和 E7000系列
  * 基于Yonah的双核低电压至强处理器系列(未经测试)
  * 至强3000, 3200, 3300, 5100, 5300, 5400, 5500, 5600, 6500, 7400, 7500 系列
> VIA:
  * 威盛Nano系列
  * C7系列和C7衍生处理器.

4.我是Window XP(SP2)用户，为何我在使用程序时会经常蓝屏死机？

这是Microsoft(微软)的一个已知的系统故障，当XP SP2 用户在运行设置了兼容Vista以上操作系统UAC权限控制的应用程序是会导致系统崩溃。(仅有Windows XP SP2版的用户会遇到此问题)。

解决方案：
<font color='#F00'>建议您及时升级您的操作系统至至少XP SP3<a href='http://support.microsoft.com/kb/322389/zh-cn'>[升级方法</a>]。注意：微软对Windows XP的支持将于2014年4月8日结束。如果你在支持结束后运行此操作系统，则无法获得Windows的安全更新和微软的技术支持。使用最新版本的window可以获得更佳的用户体验。</font>如果你暂时不想或不能升级您的操作系统，请参考下面的[知识库文章](http://support.microsoft.com/kb/921337/zh-cn)http://support.microsoft.com/kb/921337/zh-cn，并及时安装相应的补丁程序。