# 如何在AirPods Pro上安装测试版固件(以及为什么应该安装)

> 原文:[https://life hacker . com/how-to-install-beta-firmware-on-your-ai rpods-pro-and-w-1847348495](https://lifehacker.com/how-to-install-beta-firmware-on-your-airpods-pro-and-w-1847348495)

继 iPhone、iPad和Mac之后，ai rpods Pro加入了苹果设备获得测试版更新的行列。苹果现在将发布AirPods Pro 的定期测试版更新，任何人都可以使用苹果开发者账户安装。

Watch

这个测试版可以让你在正式发布之前访问即将到来的特性。有了第一个AirPods Pro beta，这意味着你将测试出环境噪音降低模式和[face time通话的空间音频](https://lifehacker.com/which-apple-devices-and-video-services-support-spatial-1845077927) 功能。

要安装这个测试版，你需要在Mac上运行iOS 15 Developer Beta 3或更高版本，以及Xcode 13 Beta 3。在开始之前，需要注意的是，如果出现问题，AirPods Pro上的固件无法降级；你必须等到一个更新发布后才能消除任何错误。

## 如何在iPhone上安装 AirPods Pro测试版配置文件

虽然激活AirPods Pro测试版的整体过程非常不同，但如果你已经安装了 [iOS 15开发者测试版](https://lifehacker.com/how-to-enroll-in-the-ios-15-developer-beta-right-now-1847158717) ，那么安装测试版配置文件的过程将会很熟悉。

1.  在你的iPhone上，进入苹果开发者网站 的 [下载部分。](https://developer.apple.com/download/)
2.  登录后，点击“下载”部分旁边的**下拉**图标，选择“**更多**”选项。
3.  F 找到“AirPods Pro Beta”部分，点击“**查看详情**按钮。
4.  选择“**iosairpods seed . mobile config**”配置文件，点击“**允许**按钮安装。
5.  打开“**设置**app，点击顶部的“**配置文件下载**选项，选择“**安装**选项，将配置文件安装到您的设备上。输入您的设备密码进行鉴定。
6.  T ap " **再次安装**，最后点击" **Done** 按钮完成该过程。

## 使用xcode启用airports pro beta更新

AirPods Pro的测试版现已安装在你的iPhone上，但实际安装测试版更新的过程不同于iOS和iPadOS的其他开发者测试版。

这涉及到在你的Mac上使用Xcode，尽管只是为了认证。在开始之前，请确保您运行的是最新的Xcode beta版(Xcode 13 Beta 3)。

1.  首先，将AirPods连接到iPhone，然后将iPhone连接到Mac。
2.  在Mac上启动Xcode beta应用程序。你不需要做其他任何事情。打开就够了。)
3.  在你的iPhone上，打开“**设置**应用，进入“**开发者**板块。
4.  一直滚动到页面底部并选择“**预发布测试版固件**”选项。
5.  你会在顶部找到你配对的AirPods Pro。轻按它旁边的开关，为AirPods Pro启用测试版软件更新。点击“**同意**按钮同意苹果的条款和条件，你就可以开始了。

要触发更新，请将AirPods Pro充电至100%，将它们连接到iPhone，然后合上手机套上的铰链。

要了解你的固件是否确实已经更新，请前往**设置** > **蓝牙**，点击AirPods Pro旁边的“ **i** ”按钮，并检查固件编号。

## 如何移除AirPods Pro beta固件

虽然您不能回滚固件更新，但您可以退出测试版，等待稳定的更新。

打开**设置**app，进入**通用** > **概要&设备管理** > **AirPods Pro‌固件概要**。在这里，轻按“**移除描述文件**”选项，从您的设备中移除AirPods Pro beta描述文件。