# 你需要立即更新 Windows

> 原文：<https://lifehacker.com/you-need-to-update-windows-right-now-1848909833>

昨天(5 月 10 日)是微软的“补丁星期二”，也不容忽视。新系统更新补丁 [75 个 Windows 安全漏洞](https://msrc.microsoft.com/update-guide/) ，包括三个零日漏洞——其中一个已经被积极利用，使您必须尽快保护您的计算机。



微软将零日漏洞定义为在有补丁之前公开或被利用的任何漏洞。如果我们按照这里的定义，这些零日漏洞中的两个之前已经公布，但没有被利用(据我们所知)，因为微软确认第三个*已经被利用*。

被利用的漏洞标识为 [CVE-2022-26925](https://msrc.microsoft.com/update-guide/en-US/vulnerability/CVE-2022-26925) ，是一个 Windows LSA 欺骗漏洞。以下是微软对该问题的描述:

> 未经身份验证的攻击者可以调用 LSARPC 接口上的方法，并强迫域控制器使用 NTLM 向攻击者进行身份验证。此安全更新检测 LSARPC 中的匿名连接尝试并禁止它。

本质上，这个缺陷允许坏人劫持认证过程:Windows 将认为这些用户已经正确地认证了他们自己，并且将毫无价值地授予他们提升的权限。从这里，这些用户可以接管一个域控制器，给他们一个危险级别的访问 Windows 服务器的权限。

与这里确定的其他 74 个漏洞不同，包括两个零日漏洞，这种利用不是理论上的:它可以在任何没有安装补丁的系统上被利用。然而，现在人们关注的是另外两个零日漏洞，它们也可能在任何时候变成被利用的漏洞。这两个漏洞被识别为拒绝服务漏洞[【CVE-2022-22713](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2022-22713)和远程代码执行漏洞[【CVE-2022-29972](https://msrc.microsoft.com/update-guide/en-US/vulnerability/CVE-2022-29972)。

虽然 75 个补丁是一个很大的修复量，但也算不上破纪录。上次我们覆盖了一个 Windows 补丁， [微软已经修复了 128 个漏洞](https://lifehacker.com/you-need-to-patch-these-128-security-bugs-on-your-pc-1848787694) 。然而，这并不削弱这次更新的重要性。 T 为了保护自己免受这三个安全漏洞以及微软已经修补的全部问题的影响，尽快安装新的更新。有针对不同版本 Windows 的特定更新，包括 7、8.1、10、11 和 Windows Server。

## 如何在您的电脑上安装最新的 Windows 补丁

当有可用的安全更新时，Windows 会自动更新你的电脑，但你不需要坐以待毙。为了尽快保护您的系统，您可以手动触发更新。前往**设置> Windows 更新>检查更新**。

[ [哔哔声电脑](https://www.bleepingcomputer.com/news/microsoft/microsoft-may-2022-patch-tuesday-fixes-3-zero-days-75-flaws/)