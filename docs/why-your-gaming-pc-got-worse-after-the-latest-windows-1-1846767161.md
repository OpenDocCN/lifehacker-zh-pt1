# 为什么您的游戏电脑在最新的Windows 10更新后变得更差

> 原文:[https://life hacker . com/why-your-gaming-PC-get-bad-after-the-latest-windows-1-1846767161](https://lifehacker.com/why-your-gaming-pc-got-worse-after-the-latest-windows-1-1846767161)

根据众多报道，Windows 10更新KB5000842和KB5001330对在窗口模式下运行的游戏造成了恼人的性能bug。根据微软的补丁说明，“一小部分用户报告在安装KB5000842或更高版本的更新后，游戏性能低于预期。受此问题影响的大多数用户都在全屏或无边框窗口模式下运行游戏，并使用两个或更多显示器。”

Watch

如果你注意到口吃或糟糕的帧速率突然影响了你的游戏，这可能就是原因。幸运的是，这很容易解决。

过去，我们通常会建议用户 [卸载这些更新](https://lifehacker.com/how-to-uninstall-windows-10s-unnecessary-kb4532441-upda-1840390785) 来解决问题，并建议其他用户 [延迟安装它们](https://lifehacker.com/how-to-block-windows-10-updates-for-as-long-as-you-want-1844232973) 以防止性能缺陷影响他们的电脑。然而，微软正在通过Windows 10新的已知问题回滚功能推出一个官方修复程序，该功能将为您解决这个问题。

已知问题回滚(KIR)是一个相对较新的特性，它可以“在发现关键回归的情况下，快速将单个有针对性的修复恢复到先前发布的行为。”基本上，KIR可以自动禁用Windows更新中有问题的部分，而不是强迫用户卸载整个更新。通过这种方式，微软可以修复无法预见的补丁后漏洞，如最近的游戏性能问题，用户可以保留重要的安全更新。

事实上，与正常的Windows更新不同，KIR过程在后台自动进行。在过去，微软已经多次使用KIR来防止一旦发现错误就传播。

如果您安装了KB5000842和KB5001330，您只需要等待修复程序向您推出。rosoft表示，KIR可能需要24小时来修复这个漏洞，并建议如果你没有发现任何变化，就重启你的电脑。您可以通过启动注册表编辑器检查KIR是否安装在您的系统上，并查看您是否有以下注册表项:

`<small>HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\FeatureManagement\Overrides\4\1837593227</small>`

如果没有，请静观其变。删除违规更新后，您电脑的游戏性能应该会恢复正常。