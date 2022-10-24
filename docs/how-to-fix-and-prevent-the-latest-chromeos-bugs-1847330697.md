# 如何修复(并防止)最新的ChromeOS漏洞

> 原文:[https://life hacker . com/how-to-fix-and-prevent-the-latest-chromeos-bugs-1847330697](https://lifehacker.com/how-to-fix-and-prevent-the-latest-chromeos-bugs-1847330697)

Chrome OS用户报告最新系统更新中的一个严重错误，导致将其锁定在Chromebooks之外。由于某种原因，Chrome OS在安装版本更新91.0.4462.165后，用户尝试登录时无法识别谷歌账户密码。他拙劣的更新也可能导致其他严重的错误，比如引导循环。

Watch

根据[9到5谷歌](https://9to5google.com/2021/07/19/psa-chrome-os-update-locking-out-accounts/) 的消息，更新91.0.4462.165似乎不再可用，谷歌正在开发一个补丁来修复它导致的错误，有望很快推出。也就是说，为了避免这些问题，在确认谷歌的新补丁正常工作之前，不要下载或安装任何新的Chrome OS更新。如果更新已经下载但尚未安装，请勿重启设备。

如果你已经安装了Chrome OS版本91.0.4462.165，并且遇到了无法识别的密码错误，你将不得不等待新的更新出现，但是一旦它可用，你应该能够安全地重新登录。幸运的是，你将能够以访客的身份登录你的Chromebook并下载更新文件，即使主用户账户无法使用。

## 如何在访客模式下安装Chrome OS更新

1.  在Chromebook登录屏幕，点击**“以访客身份浏览”**
2.  一旦你进入，进入**设置>关于Chrome OS。**
3.  点击**“检查更新”**
4.  如果有补丁可用，更新将自动开始。

在等待补丁到来的同时，你也可以继续以访客身份使用你的Chromebook。这不是一个很好的长期解决方案，因为当你退出访客模式时，你将无法执行某些管理员级别的任务，并且所有访客账户数据——包括浏览历史和下载的文件——将被删除。不过，这总比在谷歌修复这一轮Chrome操作系统错误的时候把你的Chromebook当镇纸好。

也就是说，你也可以执行工厂重置，立即在你的Chromebook上重新获得对你的Google帐户的完全访问权限。这样做会删除*你设备上保存的所有*文件和应用，移除你的谷歌账户，并恢复默认系统设置。我们不建议恢复出厂设置，除非你绝对*必须*立即恢复Chromebook上的谷歌账户。

## 如何将Chromebook重置为出厂设置

1.  在登录屏幕上，点击并按住 **Ctrl + Alt + Shift + r键。**
2.  点击**“重启”**
3.  选择**“强力清洗”**
4.  点击**“继续”**
5.  等待复位过程开始，并遵循屏幕上出现的任何指示。
6.  出现提示时，登录您的Google帐户。

## 使用恢复实用程序恢复陷入启动循环的Chromebooks

不幸的是，这些解决方法都不适用于经历引导循环的用户。相反，你将需要使用单独的Chromebook或PC、USB拇指驱动器和 [Chromebook恢复实用程序](https://chrome.google.com/webstore/detail/chromebook-recovery-utili/pocpnlppkickgojjlmhdmidojbmbodfm?hl=en) 来创建USB ChromeOS恢复媒体。下载该实用程序，按照说明操作，然后将其插入受影响的Chromebook以重新安装Chrome OS。这就像工厂重置一样擦除你的设备，但如果你想让Chromebook恢复正常工作，这是你唯一的选择。

[ [安卓中央](https://www.androidcentral.com/second-major-chrome-os-update-bug-leaving-users-locked-out-chromebooks) ]