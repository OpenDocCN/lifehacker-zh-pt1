# 如何阻止 Windows 崩溃你的联想笔记本电脑

> 原文：<https://lifehacker.com/how-to-stop-windows-from-crashing-your-lenovo-laptop-1845132218>

一些联想笔记本电脑用户将很快找到解决 Windows 10 严重错误的方法，该错误已经导致了一系列崩溃和系统启动问题。



这些崩溃是由联想的“增强的 Windows 生物识别安全”功能和 Windows 10 版本 2004 更新中引入的变化之间不可预见的兼容性问题引起的。这是 [一个高度技术性的 bug](https://www.bleepingcomputer.com/news/microsoft/microsoft-explains-why-windows-10-is-crashing-on-lenovo-laptops) ，但核心问题是 Windows 10 版让联想用户无法在不崩溃系统的情况下用笔记本电脑的指纹传感器或网络摄像头登录。

更糟糕的是，用户已经在没有微软官方消息的情况下处理这些问题有一段时间了。Windows 10 版于 7 月推出。此后，用户报告了 2019 年和 2020 年联想 ThinkPad 设备上的多项问题，包括(通过 [联想](https://pcsupport.lenovo.com/ca/en/products/laptops-and-netbooks/thinkpad-x-series-laptops/thinkpad-x1-carbon-7th-gen-type-20r1-20r2/solutions/ht511000-problems-caused-by-enhanced-windows-biometric-security-bios-setting-thinkpad) ):

*   *开机蓝屏死机*
*   *启动联想 Vantage 时蓝屏死机*
*   *运行 Windows Defender Scan 时蓝屏死机*
*   *不能用 Windows Hello 通过人脸登录*
*   *与英特尔管理引擎相关的设备管理器中的错误*
*   *与红外摄像机相关的设备管理器出错*

这些严重的问题导致一些 ThinkPad 笔记本电脑几周无法使用。糟糕的是，联想甚至告诉客户不要更新 Windows 。

令人欣慰的是，微软最终承认了这个漏洞，并表示正在与联想合作进行永久修复。两家公司都没有表明用户什么时候可以期待它的推出，但是有一个临时的解决方法，你可以在等待的时候马上实施。

### 如何在 ThinkPad 笔记本电脑上禁用联想的“增强型 Windows 生物识别安全”

此修复将禁用有问题的生物特征安全选项，尽管需要注意的是可能会使您的设备不太安全(因此它被视为临时修复)。你还需要编辑你的 ThinkPad 笔记本电脑的 BIOS 选项，这个过程有些用户可能不熟悉。如果你不知道自己在做什么，这个过程可能会令人困惑，并有潜在的风险，但在加号栏中，ThinkPad BIOS 设置实用程序比大多数 BIOS 菜单更简单、更友好。下面是你需要做的:

1.  打开你的笔记本电脑(或者重启它，如果它已经打开的话)。
2.  在它完全启动之前，按 **F1** 打开启动中断菜单，然后再次按 **F1** 打开 BIOS 设置菜单。(如果您在此步骤中遇到问题，请查看访问 BIOS 菜单 的联想支持页面，获取进一步指导)。
3.  进入笔记本电脑的 BIOS 设置菜单后，进入**安全>可视化。**
4.  关闭**“增强的 Windows 生物识别安全性”**
5.  退出菜单，点击**“重启”**重启电脑。