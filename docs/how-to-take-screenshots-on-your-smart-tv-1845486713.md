# 如何在智能电视上截图

> 原文：<https://lifehacker.com/how-to-take-screenshots-on-your-smart-tv-1845486713>

我们都习惯于在我们的 [安卓手机](https://lifehacker.com/how-to-get-android-ps-screenshot-editing-tool-on-any-an-1823646122)[苹果设备](https://lifehacker.com/how-to-take-a-screenshot-on-iphone-x-xs-and-11-1841064538)[和电脑](https://lifehacker.com/how-to-take-a-screenshot-or-picture-of-whats-on-your-co-5825771) 上截图，但你也可以在你的智能电视或流媒体设备上截图。只是更加复杂，而且首先要看你要截图的是什么。



由于高带宽数字内容保护(HDCP)，这些设备*可以*阻止你拍摄正在观看的电影和电视节目。然而，试一试也无妨。甚至有时你需要上传设备界面的截图——例如，如果你正在进行故障诊断。

有利的一面是，你可以在 Android TV、Roku、Apple TV、Nvidia Shield 和亚马逊的 Fire TV 上不使用付费应用程序的情况下截图。下面是方法:

### 在苹果电视上截图

Apple TV 允许你在 Mac 上远程截取 Apple TV 界面的截图，但 Apple TV 的版权保护是最严格的，所以你不会在 DRM 友好的应用程序上抓取你正在观看的内容的帧。

1.  将 Apple TV 和 Mac 连接到同一个网络。
2.  在 Mac 上打开 QuickTime Player。
3.  进入**“文件”>“新电影录制”**
4.  在出现的实时馈送窗口中，从下拉菜单中选择您的 Apple TV。
5.  Apple TV 屏幕上会出现一个四位数的代码。将该代码输入 Mac 上的 QuickTime，以连接两台设备。
6.  一旦你可以在 QuickTime 中看到你的 Apple TV 界面，按 **Shift + Cmd + 5** 调出截图工具栏。点击**【抓图】**截图。

### **在**安卓电视上截图

如果你的 Android 电视设备有一个专用的遥控器应用程序，检查一下屏幕截图按钮。这是在你的电视上截屏最简单的方法。然而，并不是所有的 Android 电视都提供这样的应用程序，只有少数包含截图功能。在这些情况下，你需要一个第三方的 Android 电视远程应用程序，让你截屏，如 CetusPlay。

1.  在您的安卓电视和手机上安装谷歌 Play 商店的 [CetusPlay](https://play.google.com/store/apps/details?id=com.cetusplay.remotephone&hl=en) 。
2.  确定两台设备都连接到同一个 wifi 网络。
3.  接下来，在您的 Android 电视上启用 USB 调试。进入**设置>关于**，连续选择**“构建”**七次，直到看到“开发者模式已激活”的提示信息
4.  返回设置。进入开发者选项> USB 调试，启用**“USB 调试”**
5.  在 Android 设备上打开 CetusPlay。
6.  轻触三栏图标，然后选择**“截屏”**为您的 Android 电视截屏。

### **在** Nvidia Shield 上截图

Nvidia shield 是这个列表中唯一一个真正让你原生截图的设备——不需要第三方应用程序或外部硬件。

1.  打开 Nvidia shield 的设置应用程序。
2.  进入**“设备首选项”>“系统”>“英伟达共享”**
3.  打开 Nvidia 共享。现在可以截图了。
4.  按住 Nvidia Shield remote 或遥控器应用程序上的 Home 按钮打开共享菜单。
5.  选择**“截图。”**
6.  选择**“保存到照片”**

### **在** Roku 电视/设备上截图

Roku 用户可以使用与流媒体设备连接到同一网络的 PC 的网络浏览器抓取截图。

1.  首先，你需要在你的 Roku 设备上进入开发者模式。使用 Roku remote 或遥控器应用程序，轻按主屏幕三次，向上按钮两次，然后向右、向左、向右。
2.  选择**“启用安装程序并重启”** *或* **“禁用安装程序并重启”**(以先列出的为准)
3.  Roku 重启后，进入**设置>系统>关于。**
4.  记下设备的 IP 地址。
5.  接下来，在计算机上打开一个浏览器窗口。
6.  输入 Roku 的 IP 地址。
7.  输入您的用户名和密码登录。
8.  登录后，点击**“实用程序”**
9.  点击**“截图”**按钮，截图图像将出现在屏幕上。右键单击图片，然后选择**【保存图像】**将其下载到您的 PC。

### **在**亚马逊的 Fire TV 上截图

亚马逊 Fire TV 截图必须在安装了 ADB 平台工具的外接 PC 的帮助下拍摄。

1.  在你的 Fire TV 设备上，进入**设置>我的 Fire TV >关于>网络**。记下你的设备的 IP 地址。
2.  回到设置，然后选择**开发者选项> ADB 调试**，启用 ADB 调试模式。
3.  在您的 PC 上，下载并安装 ADB 工具。这本指南应该会让它变得简单。
4.  打开电脑上的 ADB 文件夹。 **Shift +在空白处右键单击**，然后选择**“在此打开命令窗口”**
5.  在命令提示符窗口中，运行这个命令: `adb connect "IP"`(注意:用我们在步骤 1 和 2 中获取的 Fire Stick 的 IP 地址替换“IP”)。
6.  Fire TV 的屏幕上会弹出一个连接提示。接受以完成连接。
7.  你现在可以使用命令提示符从你的电脑远程截图。运行`adb shell screencap -p /sdcard/image.png`截图。然后运行`adb pull /sdcard/image.png`将截图保存到 PC 的 ADB 文件夹中。