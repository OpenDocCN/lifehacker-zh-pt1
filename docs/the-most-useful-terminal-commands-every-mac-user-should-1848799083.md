# 每个Mac用户都应该知道的最有用的终端命令

> 原文:[https://life hacker . com/the-most-used-terminal-commands-every-MAC-user-should-1848799083](https://lifehacker.com/the-most-useful-terminal-commands-every-mac-user-should-1848799083)

Mac上的“终端”可以做一些意想不到的有用的事情，例如检查您的互联网速度，更改您在dock中看到的应用程序类型，以及帮助您在预定时间关闭Mac。还有一些功能只能用终端访问，所以如果你到现在还没怎么用终端，现在是时候改变了。

Watch

## 发起网速测试

如果你有macOS Monterey，你可以直接从终端[查看你的网速。要同时运行上传和下载速度测试，请键入以下命令并按enter键:](https://lifehacker.com/how-to-check-your-internet-speed-directly-in-macos-mont-1848211312)

`networkQuality`

如果您想一次运行一个上传和下载速度测试，使用此命令:

`networkQuality -s`

## 从dock中隐藏不活跃的应用程序

Mac上的dock有时会让人觉得太拥挤。解决这个问题的一个方法是通过 [隐藏所有不活跃的应用](https://lifehacker.com/8-ways-to-make-your-mac-s-dock-more-useful-1848720074) 。您可以通过一个简单的终端命令来实现。

`defaults write com.apple.dock static-only -bool true; killall Dock`

要将dock恢复到其原始状态，请使用以下命令:

`defaults write com.apple.dock static-only -bool false; killall Dock`

或者，如果您使用以下命令，也可以将Mac的dock重置为出厂默认设置。

`defaults delete com.apple.dock; killall Dock`

## 重新启动Finder

发现者就像一个无敌boss从 [那个游戏大家一直在说](https://lifehacker.com/the-out-of-touch-adults-guide-to-kid-culture-what-exac-1848639580) 。您可以退出或强制- 退出Mac上除Finder之外的所有应用程序。不过这个小秘籍 [会帮你重启Finder](https://lifehacker.com/add-quit-to-the-finder-menu-333819) ，在app卡顿的时候很有用。

`killall Finder`

您还可以添加一个选项，让您从菜单栏中退出应用程序(在Finder中意味着重新启动)。使用此命令完成工作:

`defaults write com.apple.Finder QuitMenuItem 1; killall Finder`

这将自动重启Finder，，如果你点击屏幕顶部的 **Finder** 菜单，你会看到一个名为**退出Finder** 的新选项。

要隐藏这个选项，使用这个命令:

`defaults write com.apple.Finder QuitMenuItem 0; killall Finder`

## 保持Mac的显示器处于唤醒状态

一个简单的终端命令可以让您保持Mac的显示器处于唤醒状态。若要阻止Mac显示器无限期进入睡眠状态，请打开“终端”并使用此命令:

`caffeinate`

当你准备好让Mac的屏幕像往常一样进入睡眠状态时，按下键盘上的 **Control + C** 。

您也可以使用以下命令让显示器保持一个小时的清醒状态:

`caffeinate -u -t 3600`

您可以随意更改该命令结束时的持续时间。该值必须以秒为单位，因此如果您想让显示器保持10分钟的清醒状态，您可以将该数字替换为600。

## 计划关闭

您可以使用此命令在预定时间关闭Mac:

`sudo shutdown -h +30`

这里+30表示您计划在30分钟后关闭。你可以随意更改号码。类似地，您可以使用以下命令安排重启:

`sudo shutdown -r +30`

## 创建ASCII艺术横幅

对于那些感觉有创造力但缺乏成为艺术家的技能的人来说，Mac上的终端可以创造美丽的ASCII艺术。

`banner -w 50 Lifehacker`

在这个命令中，-w后面的数字是ASCII图片的宽度，以像素为单位，Lifehacker是文本。您可以替换这些值来创建您自己版本的作品。

## 更改默认屏幕截图格式

macOS有一个相当强大的截屏工具，默认以PNG格式保存你的屏幕照片。如果您想要将它更改为JPG，请将它粘贴到“终端”中:

`defaults write com.apple.screencapture type JPG`

您可以在同一个命令中用PDF或TIFF替换JPG，以便在您的屏幕截图中使用这些格式。

## 无需打开浏览器即可下载文件

只要您有拷贝到剪贴板的直接下载链接，或者您已经记住了它，您就可以使用“终端”来下载文件，而无需使用浏览器。这是您需要的命令:

`curl -O URL`

请注意-O是大写的O，而不是零，您必须将URL替换为下载链接，此命令才能运行。

## 复制和粘贴文件

您可以使用ditto命令直接从“终端”将文件从一个文件夹拷贝和粘贴到另一个文件夹。

`ditto -V [old folder] [new folder]`

此处[旧文件夹]应替换为原始文件夹的路径，[新文件夹]应指向您要粘贴这些文件的文件夹。

## 查看终端命令的历史记录

如果您想要检查到目前为止使用过的所有终端命令，请尝试以下方法:

`history`