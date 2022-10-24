# 为什么我的电脑在启动时总是试图打开一个文件？

> 原文：<https://lifehacker.com/why-is-my-pc-always-trying-to-open-a-file-when-it-boots-1846357048>

有时候，你的 Windows PC 似乎有自己的想法——启动程序、窗口、浏览器标签或其他任何东西，无需你的直接输入。对于这个活动来说，总有一个理由*。你的系统还没有 [变得有知觉](https://www.youtube.com/watch?v=I8a5L_e2qCM) 。然而，追踪造成这种混乱的原因总是一件有趣的事情。这正是我们将在本周的[**Tech 911**](https://lifehacker.com/c/tech/tech-911)Q&a 中讨论的内容。*

Watch

参考上图，Lifehacker 读者**阿比德米**写道:

> 当我尝试将我的 911 登录到我的新电脑时，它一直显示这个错误。我很困惑。

### 什么是“3.26.zip”，为什么你的电脑试图打开它？

我将向您介绍几个可能导致您遇到的问题的潜在选项。首先，也是最重要的一点，你的系统上可能有某种恶意软件试图在你背后执行操作。你的系统一直试图打开的那个“3.26.zip”文件感觉非常可疑，这使我认为这可能是你所面临的问题的根源。

你应该找一个有用的反恶意软件工具(比如 Malwarebytes 的免费工具)，扫描你的系统，一旦它解决了你电脑上的任何问题，你就可以松口气了。同时，也运行一次全面的 [Windows Defender](https://lifehacker.com/why-you-should-use-windows-defenders-ransomware-prevent-1837311176) 扫描。

有点奇怪的是，你的系统试图打开的桌面上的这个神秘文件显然与 911.re 代理服务有关，这是一种人们通常用来在网上隐藏自己 IP 地址的工具。如果你不知道这意味着什么，你没有注册，也没有试图在你的系统上安装任何类型的代理服务，那么我会开始紧张。

可能是时候备份你的数据并从头开始重新安装 Windows 10 了， [只是为了确保](https://lifehacker.com/the-ultimate-guide-to-reinstalling-windows-from-scratch-1832897572) 你的电脑上没有任何反恶意软件或病毒扫描程序无法捕捉的东西。不过，先运行这些。如果您对结果不满意，全新的驱动器格式和安装将为您提供最好的机会，让您摆脱任何可能困扰您的问题。

如果我错了，你完全知道“3.26.zip”是什么，你只是想知道为什么当你启动系统时 WinRAR 会一直启动，我的猜测是 Windows 10 的启动序列中发生了一件奇怪的事情导致了这一点。你应该可以通过访问两个地方之一来检查这一点:**启动应用**(点击开始按钮并选择结果后键入“启动”)或 Windows 10 **任务管理器>启动。**

当然，总有一个好的启动文件夹:*C:\ Users \[您的用户名]\ AppData \ Roaming \ Microsoft \ Windows \开始菜单\程序\启动*

在这种情况下，我怀疑你可能在这些位置中的某个位置有什么东西触发了 WinRAR 的启动——可能是安装变得奇怪的结果，或者是每当你启动系统时弹出有用实用程序的任何其他短暂的数字混乱。

如果你找不到任何东西，你可以尝试卸载 WinRAR，删除它。ZIP 文件，看看当你启动你的电脑时是否还有其他奇怪的事情发生。如果没有，太好了！考虑切换到另一个提取工具，如 [7zip](https://www.7-zip.org/) 前进。

如果你的电脑上有其他你不认识的应用程序，请快速搜索它们，以帮助你确定是否应该禁用它们。如果其中任何一个是明显的恶意软件，那么，这就是你的答案。

但是我想得越多，就越觉得你的系统被感染了，这是基于正在发生的行为*和*的名称/内容。桌面上的 ZIP 文件。除了 Malwarebytes 的实用程序和 Windows Defender 之外，你可能还想考虑使用像 [Avast 的反病毒](https://support.avast.com/en-ae/article/132/) 这样的工具来运行系统的启动时扫描——如果我是正确的，Malwarebytes 没有这个功能。您也可以尝试在其设置中启用 Malwarebytes' [rootkit 扫描器](https://forums.malwarebytes.com/topic/232038-option-to-scan-the-boot-sequence/) 。这应该是你对付你遇到的任何恶意软件所需要的全部火力，但是就像我说的，总有“销毁并重装”的方法。

* * *

*<small>你是否有一个让你夜不能寐的技术问题？厌倦了对您的 Windows 或 Mac 进行故障诊断？寻找关于应用程序、浏览器扩展或实用程序的建议来完成特定任务？让我们知道！在下面的评论或者邮件中告诉我们</small>*[*<small></small>*](mailto:david.murphy@lifehacker.com?subject=Tech%20911)<small>*<small>。</small>T15】*</small>

<small></small>