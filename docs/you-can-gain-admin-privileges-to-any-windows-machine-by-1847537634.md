# 你可以通过插入 Razer 鼠标获得任何 Windows 机器的管理权限

> 原文：<https://lifehacker.com/you-can-gain-admin-privileges-to-any-windows-machine-by-1847537634>

在 Windows 中，并非所有用户都是平等的。在没有管理员访问权限的情况下，您可以使用电脑，但不允许您安装某些应用程序或执行命令，并且您通常被阻止完全控制电脑。但现在，你可以在任何 Windows 10 机器上授予自己系统权限，只需简单地通过 [插入 Razer 键盘或鼠标](https://www.bleepingcomputer.com/news/security/razer-bug-lets-you-become-a-windows-10-admin-by-plugging-in-a-mouse/) 。那似乎...不好。



通常，不同的“用户权限”对 Windows 来说是一件好事。它保护您的系统免受滥用这些特权的人的侵害，不管是恶意的还是无意的。当您拥有管理员(或系统)权限时，您可以完全控制 Windows，因此将该权限授予任何人都是危险的。

插上右鼠标就能完全控制电脑的想法听起来比电视黑客更不现实，但这是真的。当你插入其中一个 Razer 外设时，Windows 会自动下载 [Razer Synapse](https://www.razer.com/synapse-3) ，该软件控制你鼠标或键盘的某些设置。所述 Razer 软件具有系统特权，因为它从具有系统特权的 Windows 进程启动。

但这不是漏洞发挥作用的地方。安装软件后，Windows 的安装向导会询问您要将它保存到哪个文件夹。当您为文件夹选择新位置时，您会看到“**选择文件夹**”提示。按住 Shift 键并点击右键，可以选择“**打开 PowerShell 窗口这里**，将会打开一个新的 PowerShell 窗口。

因为这个 PowerShell 窗口是从具有系统特权的进程启动的，所以 PowerShell 窗口*本身*现在具有系统特权。实际上，您已经将自己变成了机器上的管理员，能够在 PowerShell 窗口中执行您能想到的任何命令。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1429049506021138437&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1429049506021138437&autosize=1) 

这个漏洞是由用户 jonhat 在 Twitter 上首次曝光的，他试图首先联系 Razer，但没有成功。Razer 最终跟进，确认补丁正在工作中。然而，在该补丁可用之前，该公司无意中销售了一些工具，使黑客攻击数百万台计算机变得容易。

## 如何保护你的电脑免受 Razer 漏洞的攻击

虽然最好的解决办法是等待 Razer 在他们那边修补这个错误，但我们不知道这需要多长时间。如果你现在想保护你的电脑免受 Razer 外设潜在黑客的阴谋，你可以禁用你电脑的 USB 端口。

现在，不是每个人都应该这样做。如果你需要你的鼠标、键盘或其他基本外设的 USB 端口，那么你不应该禁用这些端口。如果您的电脑支持蓝牙鼠标和键盘，或者如果您使用笔记本电脑，这种方法对您来说更安全。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-gDps3fGqA0k&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-gDps3fGqA0k&start=0) 

有各种各样的(复杂的)方法可以做到这一点，但是最简单的方法是通过设备管理器。右键点击**这台电脑**，然后点击**管理**点击**设备管理器**，然后点击**通用串行总线控制器旁边的箭头。**在这里你可以找到你电脑上所有的 USB 控制器。您可以右键单击这些项目，然后选择“ **Disable** ”来禁用它们。

当您准备好重新启用您的 USB 端口时，您可以遵循这些相同的说明，并选择“ **Enable** ”来代替。请记住:这个漏洞需要有人将他们的 Razer 鼠标物理连接到您的 PC，所以除非您经常将您的计算机放在户外，否则您的计算机面临的风险很低。

**更新:**周二下午，Razer PR 向我们发布了以下声明:

> 我们了解到一种情况，在一个非常特殊的用例中，我们的软件在安装过程中为用户提供了更广泛的机器访问权限。T3】
> 
> ***我们已经调查了这个问题，目前正在对安装应用程序进行更改以限制这种使用情况，并将很快发布更新版本。使用我们的软件(包括安装应用程序)不会让未经授权的第三方访问机器。*T3】**
> 
> ***我们致力于确保我们所有系统和服务的数字安全，如果您遇到任何潜在的失误，我们鼓励您通过我们的 bug bounty service 报告，Inspectiv:***[***【https://app.inspectiv.com/#/sign-up***](https://apc01.safelinks.protection.outlook.com/?url=https%3A%2F%2Fapp.inspectiv.com%2F%23%2Fsign-up&data=04%7C01%7CWill.Powers%40razer.com%7C5d5232b1bc5347bbdbc108d966479bbd%7Cfdadce6e7f5e49db8f226a87331a9135%7C0%7C0%7C637653280023520620%7CUnknown%7CTWFpbGZsb3d8eyJWIjoiMC4wLjAwMDAiLCJQIjoiV2luMzIiLCJBTiI6Ik1haWwiLCJXVCI6Mn0%3D%7C1000&sdata=1weRp5V%2Bq4aHsWxwUvYZrGIGFmbIVRple6E9CYqxy28%3D&reserved=0)

*这篇文章是在 8 月 24 日上午 10:28 编辑的，添加了关于禁用电脑 USB 端口的内容。*