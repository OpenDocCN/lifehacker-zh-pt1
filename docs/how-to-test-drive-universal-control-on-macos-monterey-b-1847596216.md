# 如何在 macOS Monterey Beta 上试驾通用控制

> 原文：<https://lifehacker.com/how-to-test-drive-universal-control-on-macos-monterey-b-1847596216>

苹果在 WWDC 2021 年 的 [宣布的最令人兴奋的功能之一是通用控制。这项功能可以让你在多台 MAC 和 iPads 之间无缝切换光标和键盘。事实上，它是如此的无缝，没有设置的必要。您可以将光标从一个设备滑动到另一个设备，只需将光标从一个屏幕的边缘推至旁边的屏幕。](https://lifehacker.com/the-10-coolest-ios-15-features-announced-at-wwdc-2021-1847048865)

Watch

这项功能将在 macOS Monterey 和 iPadOS 15 中提供，但在发布时不会提供。但是多亏了张的开发，测试这个功能还是有可能的。如果您的两台 MAC 电脑运行的是 macOS Monterey Beta 5，您可以使用 Plist 文件来启用隐藏代码。遗憾的是，现在还没有办法在 iPad 上启用这一功能，所以你需要等到最终版本才能在 MAC 和 iPad 之间使用它。

## 如何在 macOS Monterey Beta 中启用通用控制

如果你已经在运行 macOS Monterey beta 5，你所要做的就是下载一个文件并把它放在 Library 文件夹中。看看下面的步骤。

头转向 [张的 GitHub 页面](https://gist.github.com/zhuowei/960586f474b68f5734af2339fbcbbc12) 为“Ensemble.plist”文件。在这里，右键单击“ **Raw** ”按钮，将链接的文件下载到您的桌面(它会在一个”。plist”扩展)。

现在，打开终端，粘贴以下命令。

> sudo mkdir-p/Library/Preferences/feature flags/Domain/

这将创建文件夹。如果您无法创建该文件夹，您可能需要 [禁用系统完整性保护](https://developer.apple.com/documentation/security/disabling_and_enabling_system_integrity_protection) 。现在，让我们使用终端命令打开文件夹。键入以下命令，然后按 Enter 键。

> 打开/资源库/首选项/FeatureFlags/Domain/

既然域文件夹已经打开，只需将“Ensemble.plist”文件拖到该文件夹中。输入您的管理员密码进行确认。移动文件后，重新启动 Mac 以启用该功能。在您想要使用通用控制功能的所有 MAC 上重复此过程。

该功能仅适用于 2016 年及以后的 MAC，并且启用了 iCloud 和 Handoff。

您可以通过转至“**系统偏好设置**”来确认该功能已激活。在这里，转到“**显示屏**部分。在“添加显示器”下拉列表中，您会看到“链接键盘和鼠标”部分。这意味着该特征是活动的。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1432097899958112261&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1432097899958112261&autosize=1) 

要在两台 MAC 之间使用通用控制，只需将它们并排放置，确保 iCloud 和 Handoff 已启用，只需将光标从屏幕的一边推到另一边。

[ [9to5Mac](https://9to5mac.com/2021/08/29/you-can-partially-enable-universal-control-in-macos-monterey-beta-5-heres-how/)