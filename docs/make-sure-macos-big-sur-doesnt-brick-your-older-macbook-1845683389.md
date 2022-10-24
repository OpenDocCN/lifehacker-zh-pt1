# 确保 macOS Big Sur 不会损坏您的旧 MacBook

> 原文：<https://lifehacker.com/make-sure-macos-big-sur-doesnt-brick-your-older-macbook-1845683389>

向雷德蒙的工作人员道歉，但我通常会将“升级到新版本操作系统后的灾难”与微软 Windows 10 的巨大功能发布联系起来。然而，本周轮到苹果享受一些尴尬:根据 [到](https://www.reddit.com/r/MacOS/comments/jue7n5/big_sur_update_bricked_mid2014_13_mbp/) [众多](https://www.macrumors.com/2020/11/15/macos-big-sur-update-bricking-some-macbook-pros/) [报道](https://news.ycombinator.com/item?id=25102026) ，升级到 macOS 大苏尔据称 [砖块](https://mrmacintosh.com/macos-big-sur-11-list-of-serious-install-upgrade-issues-updated/)2013 年末和 2014 年初 MacBook Pros。



不过，奇怪的是。这些问题并不仅仅局限于这些 MacBooks。正如一位 [的 Reddit 用户](https://www.reddit.com/r/MacOS/comments/jue7n5/big_sur_update_bricked_mid2014_13_mbp/gccvtil/?utm_source=reddit&utm_medium=web2x&context=3) 写道:

> *“我有一个 2015 年年中，它或多或少也是如此。黑屏上有我的登录图片/名字，一个青色轮廓的黑色光标(那个很奇怪)和一个在屏幕左上角闪烁的文本栏。就像我需要登录却没有办法登录一样。*
> 
> *安全引导，冗长，单用户等都不做。最终我得到了恢复启动工作，现在，在苹果支持的要求下，我再次重新安装卡特琳娜。"*

这位用户非常幸运地找到了手头问题的解决方案。我见过很多运行 2013-2014 款 MacBooks 的人最终系统瘫痪的例子，通常的故障诊断技巧似乎都没有帮助，苹果目前也没有很好的解决办法。正如一位 [的主人写的](https://discussions.apple.com/thread/252033547) :

> *“我的 Macbook Pro Retina 2014 年中期 si 死在大苏尔更新之后。按下电源按钮后，它仍然是黑屏。显示器后面的苹果打开了，但是诺丁汉发生了别的事情。*
> 
> *我已经尝试在安全/恢复模式下重置 PRAM 或 Booking，但没有结果。*
> 
> 我能做什么？"

和 [另一个](https://discussions.apple.com/thread/252033547?answerId=252033547021#252033547021) :

> *“同样的问题在这里。在与苹果在线一小时后，他们将此归咎于我笔记本电脑的“硬件问题”。他们什么也做不了。他们不会给我打折买新电脑，因为商店都关门了，我只能靠自己了。甚至无法从电脑上获取信息。”*

### 推迟安装 macOS 大苏尔

在我们开始故障诊断之前，让我澄清一下:**现在不要在你的旧 MacBook 上安装 MAC OS Big Sur**。如果你实在等不及了，那么在这样做之前，确保你已经备份了你的整个系统——我真心希望你不要把它安装在你每天都需要使用的系统上。将它安装在你“有趣”的 MacBook 上，而不是你工作或与外界交流所需的那台。

如果你发现你已经通过安装 macOS Big Sur 阻止了你的旧 MacBook，开始联系 [苹果支持](https://support.apple.com/) 寻求帮助。虽然老实说，这个问题在这一点上是如此之新，你可能需要给它一点时间，直到苹果公司拿出一个官方修复程序，到那时你可能能够免费解决这个问题。苹果甚至可能有一个可靠的解决方案，你可以在家里用它让你的 MacBook 再次工作(除非它真的死在水里)。

如果灾难已经发生，你真的需要尽快进入你的笔记本电脑，你有几个选择。(都不直截了当。)

### 如何修复被大苏尔砖砌的旧 MacBook

与往常一样，您可以尝试标准的“ [重置 NVRAM 和 PRAM](https://support.apple.com/en-us/HT204063) ”技术，看看它们是否为您做了什么。否则，你可以尝试启动进入 [macOS 恢复](https://support.apple.com/en-us/HT204904) 并从头重新安装你的操作系统。然而，我假设你已经尝试了这些步骤，但它们没有帮助。

拿到另一台 Mac——如果有必要，可以向朋友借一台——并通过 FireWire 或 Thunderbolt 端口将旧 Mac 连接到这台 it。打开另一台 Mac 并引导至其桌面。然后，按住“T”启动旧 Mac，使其进入 [目标磁盘](https://support.apple.com/guide/mac-help/transfer-files-mac-computers-target-disk-mode-mchlp1443/mac) 模式。如果幸运的话，这个磁盘应该会出现在借来的 Mac 上。打开“磁盘工具”,抹掉旧 Mac 的驱动器，然后关机。断开系统连接，再次给你的旧 Mac 加电，按住 **Option+Command+R** 或 **Shift+Option+Command+R** 来启动 macOS 的“ [互联网恢复](https://support.apple.com/en-us/HT201314) ”功能。这个 [*应该*](https://forums.macrumors.com/threads/macos-big-sur-update-bricking-some-older-macbook-pro-models.2268438/post-29245622) 帮忙。否则，您可以使用正常恢复模式恢复到 macOS 的早期版本。如果第一次不成功就继续尝试(或前几次)。)

如果你有更新的 MacBook，你也可以尝试“ [复活](https://support.apple.com/en-au/guide/apple-configurator-2/apdebea5be51/mac) ”你 Mac 的 T2 安全芯片的固件。不能保证这一定有效——除非你想丢失 Mac 硬盘上的所有数据，否则不要*删除*,但这值得一试。

否则，如果你方便的话， [拔掉你的 MacBook 的 I/O 板](https://discussions.apple.com/thread/252033190)[应该可以让你重新工作](https://www.ifixit.com/Guide/MacBook+Pro+13-Inch+Retina+Display+Late+2013+I-O+Board+Replacement/27284)——显然，你失去了很多连接。要做到这一点，你需要打开你的 MacBook，这排除了所有人，除了真正绝望的人(他们有五瓣螺丝刀)。

和...就是这样。我还没有遇到其他可靠地解决这个问题的修复，更不用说其他绝望的瞎猜了。我最好的建议是不要升级到 macOS Big Sur。或者，如果你必须，尝试先升级到 [macOS Catalina](https://apps.apple.com/us/app/macos-catalina/id1466841314?mt=12) ，看看效果如何，如果你没有遇到任何问题，对你的系统进行完整备份，然后*再*升级到 macOS Big Sur。

展望未来，请记住这一点:如果你的 Mac 电脑对新操作系统的兼容性已经到了极限——或者，老实说，即使不是这样——也许最好等一周左右再升级，以防苹果公司面临灾难。不要做小白鼠。你肯定不想去苹果天才吧，尤其是在疫情期间。