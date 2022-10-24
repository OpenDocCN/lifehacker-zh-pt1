# 如果 BitLocker 不让我进入，我如何访问我的外部驱动器？

> 原文：<https://lifehacker.com/how-can-i-access-my-external-drive-if-bitlocker-wont-le-1846888293>

![](../Images/aef335eb562a1da6957ce25a574b4aa1.png)

#### **从 Lifehacker 的高级技术编辑那里获得免费技术支持**

*您是否有一个让您夜不能寐的技术问题？我们很乐意在未来的 Tech 911 专栏中回答这个问题！给 david.murphy@lifehacker.com 的*[](mailto:david.murphy@lifehacker.com?subject=Tech%20911)**发一封电子邮件，描述你的问题，并确保在主题栏中写上“科技 911”。**



*Watch*

*加密是一件奇妙的事情。虽然我没有在家里的 Windows 桌面上运行全硬盘加密——这是 BitLocker 提供的——但这只是因为我是唯一一个使用我的系统的人，我并没有在上面保留任何有价值的东西。(我所有的个人文件和任何我本来要加密的东西都存在一个通常关机的 NAS 盒上。)*

*我这样做，一部分是因为我懒，一部分是因为我想让我的电脑达到最高性能，还有一部分是因为我害怕有一天加密出错——或者当我需要重新安装 Windows 10 时，我对我必须做的一切都心不在焉——我无法访问我的数据。*

*《生活黑客》读者乔恩对这种情况再熟悉不过了。正如他为本周的[**Tech 911**](https://lifehacker.com/c/tech/tech-911)Q&A:*

> **“我有一个 Western Digital 外置硬盘，硬盘上的一个文件夹是用 Windows Bitlocker 加密的。我忘记我这样做了，重新安装了 windows，再也无法访问文件。有办法解决这个问题吗？”**

### *你写下了你的恢复密钥，对吗？*

*这正是我*不想*处理的那种情况，这就是为什么我宁愿不使用 Bitlocker。我将坚持使用类似于 [VeraCrypt](https://www.veracrypt.fr/en/Home.html) 的东西，这样我的操作系统就不会与加密过程捆绑在一起。我只需要记住一个巨大的密码，我可以将它存储在密码管理器中，写下来，贴在我的桌子下面，或者通过你能想到的任何其他防间谍方法保存。*

*在外部驱动器上启用加密时，应该会提示您保存 BitLocker 恢复密钥。如果你不记得这样做了，或者你不知道你把钥匙藏在哪里，这是我们将要处理的主要问题。*

*解锁加密驱动器 [很简单](https://www.jeroentielen.nl/howto-reinstalling-windows-on-a-bitlocker-encrypted-system/) 。理论上，你所要做的就是启动文件浏览器，右键点击驱动器，然后解锁。系统会提示您输入初始化 BitLocker 时设置的密码或 PIN，仅此而已。*

*如果您不知道用于设置 BitLocker 的密码或 PIN，这就是恢复密钥发挥作用的地方。它基本上是你的数字救生工具。如果你没有，你就完了。这就是加密的本质。有没有一种简单的方法可以绕过它，访问你的文件，那么，加密硬盘有什么意义呢？任何物理或远程访问您的系统的人都可以在几分钟的工作后直接进入您的数据，完全使恢复密钥失效。*

*也就是说，即使所有这些关于恢复键的讨论没有唤起你的记忆，你也有一条生命线。在设置 BitLocker 加密时，您可能已将该密钥保存到您的 Microsoft 帐户中。如果有，你可以在 这个链接找到 [**。微软的密钥档案非常全面，只要你曾经把它保存到你的账户中。我只是看了一下链接，找到了我多年前的台式电脑的钥匙。**](https://onedrive.live.com/recoverykey)*

*如果它不在那里，并且你不记得你可能在哪里存储了所述密钥，就认为你的数据不见了。嗯，从技术上讲，它还在那里，只是你没有办法接近它。而且，不，没有你可以使用的变通办法，也没有你可以尝试的暴力技术来恢复访问。正如流行的 M3 数据恢复工具 [的开发者形容](https://www.m3datarecovery.com/bitlocker-drive-data-recovery/unlock-bitlocker-without-password-recovery-key.html) :*

> **“众所周知，BitLocker 是一种磁盘级加密解决方案。因此，如果您忘记了 BitLocker 密码并丢失了 BitLocker 恢复密钥，数据恢复软件(包括 M3 BitLocker 恢复)不会也不会侵入您的 BitLocker 加密驱动器。这既是一个政策问题，也是一个技术限制。”**

*我希望林克能帮到你。如果没有，您可能希望浏览一下您喜欢的常用密码，看看在设置 BitLocker 驱动器时是否可能使用了其中的一个。除此之外，这是一个有价值的提醒，即使是外部驱动器也应该备份到某个地方——理想情况下是备份到您通过物理访问保护的未加密位置，或者甚至是某种可以自行处理加密的云存储提供商。*

* * *

**<small>你是否有一个让你夜不能寐的技术问题？厌倦了对您的 Windows 或 Mac 进行故障诊断？寻找关于应用程序、浏览器扩展或实用程序的建议来完成特定任务？让我们知道！在下面的评论或者邮件中告诉我们</small>*[*<small></small>*](mailto:david.murphy@lifehacker.com?subject=Tech%20911)<small>*<small>。</small>T15】*</small>*

*<small>*<small></small>*<small>T4】</small></small>*

*<small><small></small></small>*