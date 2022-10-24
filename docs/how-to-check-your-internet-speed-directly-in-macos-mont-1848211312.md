# 如何在macOS Monterey中直接查看自己的网速

> 原文:[https://life hacker . com/how-to-check-your-internet-speed-direct-in-MAC OS-mont-1848211312](https://lifehacker.com/how-to-check-your-internet-speed-directly-in-macos-mont-1848211312)

如果你想知道你的网速有多快(或多慢)，通常的方法是去speedtest.net、fast.com或其他任何一个网速测试网站。但是如果你有一台运行macOS Monterey的Mac，你就不需要访问任何网站来检查你的网速。现在macOS中有一个内置工具，可以让你直接从终端测试你的连接速度。

Watch

## 为什么在网速测试网站上使用终端

在Mac上尝试基于终端的速度测试有几个很大的好处。其中最大的问题是，你没有加载一个广告充斥的网站，这对你的隐私和电池寿命有负面影响。根据你电脑的运行情况，“终端”比使用浏览器要快得多，所以开始速度测试的总时间要稍微短一些。

除了那个，终端方法也只是容易执行。它绝对不需要任何编码知识或任何特殊的技术技能，这对许多人来说是一大优势；它让那些对技术不感兴趣的人有机会尝试终端，这可能对尝试其他有用的命令大有帮助，比如的一个让你 [检查你Mac上所有安装的应用](https://lifehacker.com/list-all-installed-applications-on-a-mac-with-a-termina-1708525931) 或者另一个让你 [设置睡眠定时器](https://lifehacker.com/set-your-mac-s-sleep-time-with-a-terminal-command-1691284688) 。

## 如何使用终端测试你的网速

若要使用此功能，请在Mac上打开“终端”。如果你找不到应用程序，你可以按下 **Command +空格键**打开Spotlight search并输入**终端**。终端打开后，输入**网络质量**(不需要大写)，按**回车**。

现在，只要你的Mac连接到互联网并运行macOS Monterey，速度测试就会开始。测试运行时，你会看到一个下载和上传速度的实时读数。一旦完成，终端将在 **==== SUMMARY ====** 标题下显示结果。

这个命令同时运行上传和下载速度测试，但是如果您想一个接一个地运行这些测试，您可以使用终端命令 **networkQuality -s** 。该命令将首先运行下载速度测试，然后检查您的上传速度。测试结果不受影响。