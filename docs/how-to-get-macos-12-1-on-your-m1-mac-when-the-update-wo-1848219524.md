# 当更新不出现时，如何在你的M1 Mac上安装macOS 12.1

> 原文:[https://life hacker . com/how-to-get-MAC OS-12-1-on-your-m1-MAC-when-the-update-wo-1848219524](https://lifehacker.com/how-to-get-macos-12-1-on-your-m1-mac-when-the-update-wo-1848219524)

苹果的macOS 12.1是一个有趣的更新。它最终将iOS和iPadOS的SharePlay带到了MAC OS face time——允许你在视频通话中与朋友分享你的屏幕和其他媒体——除了隐藏我的电子邮件和 [苹果音乐语音计划](https://lifehacker.com/is-the-apple-music-voice-plan-worth-the-trade-offs-1847899974) ，以及其他伟大的功能。然而，如果你正在摇动一台M1 Mac，你可能在你的计算机上根本看不到这个更新。怎么回事？

Watch

## 为什么macOS 12.1不会出现在M1的MAC电脑上还是个谜

在这个时候，我们仍然不知道交易是什么。出于某种原因，M1、M1专业版和M1 Max用户在下载12.1更新甚至在系统偏好设置中出现时遇到了问题。9to5Mac作家Bradly Chambers甚至在从Mac App Store下载了完整的macOS Monterey安装程序后，也无法获得工作的更新 。

幸运的是，一位9to5Mac的评论者提出了解决方案。评论者Jonlon有一台M1 Mac mini和一台M1 Max MacBook Pro，它们都没有在系统偏好设置中显示12.1更新。幸运的是，Jonlon想出了一个六步解决方案来让更新出现并下载，这让许多沮丧的Mac用户感到高兴:

> 1.)打开系统偏好设置>软件更新。确认没有可用的更新，并保持窗口打开。
> 
> 2.)打开应用程序>实用程序>活动监视器。

> 3.)转到查看>所有进程
> 
> 4.)搜索“com . apple . mobilesoftwareupdate . updatebrainservice”。选择它并点按“强制退出”。[ 如果这不起作用，请尝试使用“com . apple . nrd . updatebrainservice”来代替。]
> 
> 5.)12.1更新应该会出现在“系统偏好设置”中。单击立即更新。
> 
> 6.)更新可能无法下载-请使用“活动监视器”再次强制退出com . apple . mobilesoftwareupdate . updatebrainservice以开始下载。[ 同样，您可能需要改为强制退出"com . apple . nrd . updatebrainservice "。]

Jonlon不确定为什么这个方法会触发更新，我们也不确定，但是我们很高兴它会触发更新。如果你的M1、M1 Pro或M1 Max Mac找不到更新，这个过程可能是最好的解决方案——至少在苹果正式解决这个问题之前。

[ [9to5Mac](https://9to5mac.com/2021/12/14/some-users-are-not-seeing-the-macos-monterey-12-1-update-on-m1-macs/)