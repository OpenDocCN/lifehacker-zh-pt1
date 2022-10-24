# 这个实验性的功能阻止了 Chrome 占用你所有的内存

> 原文：<https://lifehacker.com/this-experimental-feature-stops-chrome-from-hogging-all-1849166263>

Chrome 是一个臭名昭著的资源猪——原因之一 [许多用户放弃了它](https://lifehacker.com/yes-you-should-quit-using-google-chrome-1844408232) 而选择了其他浏览器像 Firefox，Safari，甚至是基于 chrome 的 Edge。但是对于那些仍在使用谷歌浏览器的人来说，有一些好消息:该公司正在测试一种新的设置，可以缓解 Chrome 令人烦恼的高内存使用率。



它是这样工作的。通常情况下，Chrome 会每分钟检查一次所有打开的浏览器标签是否有更新。每次打开标签时，该过程占用额外的 RAM。如果你只打开了几个标签页(或者碰巧有很多内存)，这不是问题，但是如果你一直打开大量标签页或者在一台旧电脑上运行 Chrome，你肯定会注意到滞后和其他性能问题。

这项名为“快速强化节流”的新功能将后台标签检查减少到每五分钟一次。谷歌已经 [公布了对功能的详细解释](https://docs.google.com/document/d/1WFyfKUUxqM7uKxKOGhLiOjyY6T7QRduVcuHN0f6vJkk/edit#) ，包括 他们如何决定五分钟间隔，但关键的一点是快速密集节流有可能显著减少 Chrome 的 RAM 使用。

不幸的是，新的设置仍处于测试阶段，在主 Chrome 浏览器中不可用，但你可以通过下载最新的 Chrome Canary build 并在实验标志设置中启用该功能来提前尝试。由于 Chrome Canary 是浏览器的特殊构建，旨在对未完成的功能进行测试，因此这个和其他实验标志可能并不总是正确工作。但 Canary 也是一个真正独立的浏览器，所以你可以下载它而不用覆盖你的标准 Chrome 安装，如果你遇到问题，可以很容易地切换回安全稳定的公共版本。

## 如何在 Chrome Canary 中尝试 Chrome 新的快速密集节流设置

1.  下载安装 [Chrome 金丝雀](https://www.google.com/chrome/canary/) 。
2.  打开浏览器，然后在搜索栏中键入*chrome://flags/# quick-intensive-throttling-after-loading*，直接导航到实验标志菜单中的设置。
3.  点击**“加载后快速强化节流”**旁边的下拉菜单，选择**“启用”**
4.  当提示应用更改时，重新启动浏览器。

这些步骤完成后，Chrome Canary 中打开的背景标签将占用更少的内存。请注意，一旦快速密集节流使其成为 Chrome 的稳定版本，这些步骤将有所不同，但希望这样一个有帮助的、资源节约设置一旦最终确定，将很容易启用，甚至在默认情况下打开。

对于那些寻求在不安装和不稳定版本的情况下减少其浏览器占用空间的人来说，查看我们的指南 [关于 Chrome 为什么使用这么多 RAM](https://lifehacker.com/why-chrome-uses-so-much-freaking-ram-1702537477) 以获得如何抑制其对你的系统内存需求的提示。公平的警告:那些故障排除可能不会减少你的系统延迟太多，但是它们可以在你等待更积极的内存节省设置进入 Chrome 时提供一个权宜之计。

[ [哔哔声电脑](https://www.bleepingcomputer.com/news/google/new-google-chrome-feature-reduces-cpu-use-to-extend-battery-life/)