# 如何启用Chrome OS 91的隐藏实验功能

> 原文:[https://life hacker . com/how-to-enable-chrome-OS-91s-hidden-experimental-feature-1847036471](https://lifehacker.com/how-to-enable-chrome-os-91s-hidden-experimental-feature-1847036471)

如果你已经更新到Chrome OS 91，有几个隐藏的功能可以打开，包括一个新的垃圾桶文件夹和一个更方便的渐进式网络应用程序界面。还有一种方法可以为还没有Chrome OS的用户手动启用实时字幕。

Watch

这些功能是故意隐藏的——它们仍处于试验阶段，还没有准备好全面发布。未来的Chrome OS更新可能会将它们添加为默认功能，但如果你想提前尝试，你可以这样做。您必须尽力启用每个特性，它们可能无法正常工作，但是我们将向您展示如何工作。

## 如何启用Chrome OS的垃圾文件夹

让我们从大多数Chromebook用户想要的隐藏功能开始:一个专用的垃圾桶，就像Windows和Mac上的已删除文件容器。正如许多Chromebook用户痛苦地*意识到一样，Chrome OS不允许你恢复被删除的文件——但是你可以通过启用垃圾箱文件夹来改变这一点。*

*Chrome OS的垃圾桶打开后，删除的文件会被发送到文件夹中，它们会一直留在那里，直到你恢复它们或永远删除它们。可以从文件管理器窗口访问回收站文件夹。*

*Chrome OS trash文件夹是通过Chrome的实验标志菜单启用的:*

1.  *在新的Chrome标签中，进入:**Chrome://flags/# files-trash***
2.  *将标志设置为**“启用”***
3.  *重启Chrome，然后重启Chromebook。*

## *如何在Chrome OS 91中启用渐进式网络应用程序窗口*

*渐进式web应用程序(PWA)是基于web的应用程序，其外观和运行方式类似于本地安装的软件，但在硬盘上占用的空间更少。大多数pwa在一个窗口中运行，但会在浏览器标签中打开外部链接，使得一些pwa不如在浏览器中加载页面有效(看着你，YouTube)。*

*令人欣慰的是，谷歌将很快在Chrome OS上实现选项卡式PWA导航，这样你就可以在一个PWA窗口中打开多个链接或文档，并轻松地在它们之间切换，但如果你在Chrome flags菜单中打开这个实验性功能，你就可以提前获得该功能。*

1.  *打开一个新的Chrome标签然后进入:***Chrome://flags/# enable-desktop-pwas-tab-strip****
2.  *从下拉菜单中选择**“启用”**。*
3.  *接下来进入:***chrome://flags/# enable-desktop-pwas-tab-strip-link-capture****
4.  *将该标志也设置为**“启用”**。*
5.  *当提示保存更改时，重启Chrome。*
6.  *重启你的Chromebook。*

*下次安装PWA时，会出现一个对话框，询问您是否要运行带选项卡的PWA。*

*要使用选项卡式窗口打开您已经安装的PWAs，请右键单击桌面上的应用程序图标，然后选择**新窗口>新选项卡式窗口。***

## *如何在Chrome操作系统中打开实时字幕91*

*最后，有一个为一些用户打开实时字幕的选项。对于那些不知道的人来说，Chromebook上的Live Caption也是由人工智能支持的实时转录功能，可以将任何音频转换为Android设备上的屏幕字幕。该功能即使在音量关闭或离线时也能工作。随着Chrome OS 91的发布，预计每个人都可以看到直播字幕，但一些设备仍然没有。*

*不过，不要担心——你也许可以自己打开它。*

1.  *在Chrome浏览器窗口中，打开:**Chrome://flags/# enable-accessibility-live-caption***
2.  *将标志设置为**“启用”***
3.  *重启Chrome以应用更改。*
4.  *重启你的Chromebook。*
5.  *[查看我们的实时字幕指南](https://lifehacker.com/how-to-set-up-chrome-live-captions-on-your-desktop-1846535575) 了解如何在重启后启用(和禁用)Chromebook上的功能。*

*即使打开了标志，直播字幕也有可能不起作用，因为一些用户看到一个错误，他们的设备无法下载所需的语音文件。有一个解决方法，但这应该只是暂时的，因为它会影响转录的准确性。*

1.  *再次进入Chrome，进入**Chrome://flags/# enable-accessibility-live-caption-soda。***
2.  *从框中选择**【禁用】**。*
3.  *重启Chrome，然后重启Chromebook。*

*重新启动后，实时字幕现在应该可以工作了——但请确保您将来重新启用了**# enable-accessibility-Live-caption-soda**标志，以确保您下载了最新的语音识别文件。*

*[ [安卓警察](https://www.androidpolice.com/2021/06/03/three-hidden-chrome-os-91-features-you-should-enable-right-now/)*