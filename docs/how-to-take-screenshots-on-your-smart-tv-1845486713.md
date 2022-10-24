# 如何在智能电视上截图

> 原文:[https://life hacker . com/how-to-take-screens-on-your-smart-TV-1845486713](https://lifehacker.com/how-to-take-screenshots-on-your-smart-tv-1845486713)

我们都习惯于在我们的 [安卓手机](https://lifehacker.com/how-to-get-android-ps-screenshot-editing-tool-on-any-an-1823646122)[苹果设备](https://lifehacker.com/how-to-take-a-screenshot-on-iphone-x-xs-and-11-1841064538)[和电脑](https://lifehacker.com/how-to-take-a-screenshot-or-picture-of-whats-on-your-co-5825771) 上截图，但你也可以在你的智能电视或流媒体设备上截图。只是更加复杂，而且首先要看你要截图的是什么。

Watch

由于高带宽数字内容保护(HDCP)，这些设备*可以*阻止你拍摄正在观看的电影和电视节目。然而，试一试也无妨。甚至有时你需要上传设备界面的截图——例如，如果你正在进行故障诊断。

有利的一面是，你可以在Android TV、Roku、Apple TV、Nvidia Shield和亚马逊的Fire TV上不使用付费应用程序的情况下截图。下面是方法:

### 在苹果电视上截图

Apple TV允许你在Mac上远程截取Apple TV界面的截图，但Apple TV的版权保护是最严格的，所以你不会在DRM友好的应用程序上抓取你正在观看的内容的帧。

1.  将Apple TV和Mac连接到同一个网络。
2.  在Mac上打开QuickTime Player。
3.  进入**“文件”>“新电影录制”**
4.  在出现的实时馈送窗口中，从下拉菜单中选择您的Apple TV。
5.  Apple TV屏幕上会出现一个四位数的代码。将该代码输入Mac上的QuickTime，以连接两台设备。
6.  一旦你可以在QuickTime中看到你的Apple TV界面，按 **Shift + Cmd + 5** 调出截图工具栏。点击**【抓图】**截图。

### **在**安卓电视上截图

如果你的Android电视设备有一个专用的遥控器应用程序，检查一下屏幕截图按钮。这是在你的电视上截屏最简单的方法。然而，并不是所有的Android电视都提供这样的应用程序，只有少数包含截图功能。在这些情况下，你需要一个第三方的Android电视远程应用程序，让你截屏，如CetusPlay。

1.  在您的安卓电视和手机上安装谷歌Play商店的 [CetusPlay](https://play.google.com/store/apps/details?id=com.cetusplay.remotephone&hl=en) 。
2.  确定两台设备都连接到同一个wifi网络。
3.  接下来，在您的Android电视上启用USB调试。进入**设置>关于**，连续选择**“构建”**七次，直到看到“开发者模式已激活”的提示信息
4.  返回设置。进入开发者选项> USB调试，启用**“USB调试”**
5.  在Android设备上打开CetusPlay。
6.  轻触三栏图标，然后选择**“截屏”**为您的Android电视截屏。

### **在** Nvidia Shield上截图

Nvidia shield是这个列表中唯一一个真正让你原生截图的设备——不需要第三方应用程序或外部硬件。

1.  打开Nvidia shield的设置应用程序。
2.  进入**“设备首选项”>“系统”>“英伟达共享”**
3.  打开Nvidia共享。现在可以截图了。
4.  按住Nvidia Shield remote 或遥控器应用程序上的Home按钮打开共享菜单。
5.  选择**“截图。”**
6.  选择**“保存到照片”**

### **在** Roku电视/设备上截图

Roku用户可以使用与流媒体设备连接到同一网络的PC 的网络浏览器抓取截图。

1.  首先，你需要在你的Roku设备上进入开发者模式。使用Roku remote或遥控器应用程序，轻按主屏幕三次，向上按钮两次，然后向右、向左、向右。
2.  选择**“启用安装程序并重启”** *或* **“禁用安装程序并重启”**(以先列出的为准)
3.  Roku重启后，进入**设置>系统>关于。**
4.  记下设备的IP地址。
5.  接下来，在计算机上打开一个浏览器窗口。
6.  输入Roku的IP地址。
7.  输入您的用户名和密码登录。
8.  登录后，点击**“实用程序”**
9.  点击**“截图”**按钮，截图图像将出现在屏幕上。右键单击图片，然后选择**【保存图像】**将其下载到您的PC。

### **在**亚马逊的Fire TV上截图

亚马逊Fire TV截图必须在安装了ADB平台工具的外接PC的帮助下拍摄。

1.  在你的Fire TV设备上，进入**设置>我的Fire TV >关于>网络**。记下你的设备的IP地址。
2.  回到设置，然后选择**开发者选项> ADB调试**，启用ADB调试模式。
3.  在您的PC上，下载并安装ADB工具。这本指南应该会让它变得简单。
4.  打开电脑上的ADB文件夹。 **Shift +在空白处右键单击**，然后选择**“在此打开命令窗口”**
5.  在命令提示符窗口中，运行这个命令: `adb connect "IP"`(注意:用我们在步骤1和2中获取的Fire Stick的IP地址替换“IP”)。
6.  Fire TV的屏幕上会弹出一个连接提示。接受以完成连接。
7.  你现在可以使用命令提示符从你的电脑远程截图。运行`adb shell screencap -p /sdcard/image.png`截图。然后运行`adb pull /sdcard/image.png`将截图保存到PC的ADB文件夹中。