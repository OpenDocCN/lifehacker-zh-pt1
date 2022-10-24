# 尝试修复 macOS 的“永久屏保”错误

> 原文：<https://lifehacker.com/try-these-fixes-for-the-macos-permanent-screensaver-bug-1846088663>

一个奇怪的错误正在影响苹果 M1 系列 MAC 电脑(笔记本电脑*和台式电脑*)的一些用户，它触发 macOS 屏幕保护程序随机运行。一开始听起来还不错——谁不喜欢 Flurry 呢？——除了一个更奇怪的问题，一旦它被打开，受影响的 Mac 的屏幕保护程序就无法关闭。

Watch

如果你被这个错误击中，你基本上被锁定在你的系统之外，这似乎与 macOS 的“快速用户切换”功能有关。如果你在 MacBook 上只使用一个账户，你可能不会受到这个 bug 的影响；然而，如果你在 Mac 上有多个账户，你可能需要采取一些措施来解决这个问题，以免 [在你不方便的时候把你锁出系统](https://forums.macrumors.com/threads/what-is-going-on-here-screensaver-like-animation-spontaneously-appears-video.2273013/post-29338930) 。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-uIyQnKT6ySI&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-uIyQnKT6ySI&start=0) 

首先，如果你可以暂时只使用一个账户，那就试试吧。我知道这是一个奇怪的建议，但是如果你为一个家庭成员建立了一个新账户，而他们从未使用过，那么也许可以考虑在苹果解决这个问题之前取消这个账户(或者说家庭成员最终需要才能使用电脑)。

你也可以试试这一招，MacRumors 的评论者 [写道](https://forums.macrumors.com/threads/some-m1-macs-affected-by-fast-user-switching-screensaver-bug.2280806/post-29517962) :

> 我在我的 mini 上也有同样的问题，我试着禁用两个用户的屏保并安装了安非他命，它解决了这个问题。我希望正在进行修复，我很高兴看到我不是唯一有这个问题的人。

Apple 支持人员似乎也一直在告诉人们尝试在“终端”中输入以下命令，这会禁用登录屏幕本身的超时功能:

`sudo defaults write /Library/Preferences/com.apple.screensaver loginWindowIdleTime 0`

这应该可以防止问题影响您的 Mac。您也可以尝试“禁用”快速用户切换。我不太愿意推荐我的第一个故障诊断技术，因为**系统偏好>用户&组>登录选项**让你从菜单栏中删除 F ast U ser Sw itching 菜单，但我不相信*会禁用*它。不过，如果你想先尝试一个快速简单的修复方法，还是值得一试的。

另一个巧妙的解决方案来自这个 MacRumors [评论者](https://forums.macrumors.com/threads/some-m1-macs-affected-by-fast-user-switching-screensaver-bug.2280806/post-29518556) :

> 我发现每次都有效的解决方案是设置一个屏幕的“热角”来让显示器休眠。然后，当这个屏保 bug 出现时，只需将鼠标移到角落，让屏幕休眠几秒钟，然后再次移动鼠标将其唤醒。屏保将会停止。希望这有所帮助。

你也可以试着安装 macOS 11.2 版的，据报道它可以永久修复这个问题。否则，记住这个组合键——*Command+Option+Power Button*——如果你的屏保没有反应，就用它来让你的系统休眠。Mac 唤醒后，您应该能够像往常一样访问电脑。