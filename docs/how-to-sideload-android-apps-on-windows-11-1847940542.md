# 如何在Windows 11上侧载Android应用

> 原文:[https://life hacker . com/how-to-side load-Android-apps-on-windows-11-1847940542](https://lifehacker.com/how-to-sideload-android-apps-on-windows-11-1847940542)

Windows 11可以运行Android应用程序，就像它们是原生的PC软件一样，但在撰写本文时，只有少数几个得到了官方支持。然而，有一种方法可以将不支持的应用程序下载到Windows 11，类似于如何在Android手机上安装第三方应用程序。

Watch

你需要一些东西来完成这件事。首先，你需要加入Windows 11 Insider计划，并安装Android应用的Windows子系统。你可以从 [微软的公告博客](https://blogs.windows.com/windows-insider/2021/10/20/introducing-android-apps-on-windows-11-to-windows-insiders/) 中了解更多关于加入测试版的信息。

其次，你需要在你的电脑上安装Android调试桥(ADB)。我们有一个在Windows 10 上安装ADB的 [指南，这个过程延续到Windows 11。](https://lifehacker.com/the-easiest-way-to-install-androids-adb-and-fastboot-to-1586992378)

第三，你需要你要安装的应用程序的APK文件。你可以从可靠的来源找到这些，如APK镜报、APKPure、F-Droid、Github或XDA开发者论坛。只要确保你从你知道是安全的网站下载合法的文件(意思是非盗版的)就行了。盗版apk可能充斥着恶意软件，或者托管在不安全的域名上，你知道，下载盗版软件是非法的。

最后，你可能还需要侧装 [微G APK](https://github.com/microg/GmsCore/wiki) 以便使用检查Google Play服务验证的应用。MicroG是开源软件，本质上是复制谷歌的服务，所以你可以在其他不受支持的设备上使用应用程序。这是一个可选步骤，你必须按照下面的步骤安装MicroG，但如果你想运行任何谷歌应用或依赖Play Store验证的应用，这是必要的。

有了这些先决条件之后，让我们从侧面加载这些应用程序。乍一看这可能很复杂，但是一旦你知道了这个过程，它会很快完成。

1.  首先，从Windows 11开始菜单的**“所有应用”**部分打开Android的Windows子系统。
2.  在Android的Windows子系统设置窗口中，找到并打开**“开发者模式”**
3.  打开设置菜单顶部的“**文件”**窗口，在PC上打开Android。
4.  回到设置菜单，向下滚动并点击IP地址选项旁边的**“刷新”**(就在开发者模式开关的正下方)。一旦IP地址出现，点击**“复制”**
5.  接下来，以管理员身份打开Windows终端。进入**开始菜单>所有应用**。将鼠标悬停在**“Windows终端”**上，然后选择**更多>以管理员身份运行。**
6.  在Windows终端窗口中，使用步骤4和5中的IP地址键入命令`adb connect (IP address)`。它应该看起来像`adb connect 1234.5.6.7`
7.  按Enter键运行命令。如果一切正常，您应该看到**“连接到[IP地址]。”**我们现在可以将保存在您电脑上的APK文件下载到Android的Windows子系统上运行。
8.  回到Windows终端窗口，键入命令`adb install` ，然后用引号将文件夹路径和文件名括起来。例如，完整的命令可能看起来像`adb install “C:\com.whatsapp_2.21.21.15-212115005_minAPI16(x86_64)(nodpi)_apkmirror.com”`
9.  如果一切正常，安装开始后，您将在Windows终端中看到“正在执行流式安装”,安装完成后会看到“成功”。

仅此而已。该应用程序现已安装在你的电脑上。和其他安卓应用一样，你可以从Windows 11开始菜单运行侧装应用。它们将被列在“所有应用程序”下双击运行应用程序，它会在自己的应用程序窗口中打开。

如果由于某种原因，该应用程序无法工作，请尝试按照上面的建议安装MicroG。或者，你可以尝试在Windows 上通过Android模拟器运行应用程序。

[XDA开发者](https://www.xda-developers.com/how-to-sideload-android-apps-on-windows-11/)