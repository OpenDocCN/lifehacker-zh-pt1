# 如何修复神秘的 iPhone Wifi Bug(并完全避免)

> 原文：<https://lifehacker.com/how-to-fix-the-mysterious-iphone-wifi-bug-and-avoid-it-1847144065>

一个不寻常的 bug 目前正在破坏 iPhones 的 wifi 连接。幸运的是，这很容易避免——如果你的手机受到影响，也很容易解决——但是该死，这很奇怪吗？简而言之，f 或者某种原因，如果你的 iP hone 将连接到一个名为“%p%s%s%s%s%n，的 wifi 网络，那么设备的 wifi 将停止工作。所以不要那么做。

Watch

安全研究员 Carl Shou 首先发现了这个漏洞，并在 Twitter 上发布了这一发现。其他几个用户通过他们自己的测试确认了这个问题。在每个案例中，仅网络名称就破坏了他们 iPhone 的 wifi 功能，并阻止他们连接到其他网络。更糟糕的是，测试人员发现，即使在重启受影响的 iPhone 后，漏洞仍然存在。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1405937492642123782&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1405937492642123782&autosize=1) 

奇怪的是，这个 bug 并不影响其他网络功能，比如蓝牙或移动数据。在 Android 上连接所谓的 wifi 网络同样没有效果；t 这个 bug 似乎源于 iOS 操作系统或者 iPhone 的硬件，但是还没有人知道 *为什么*这个特殊的 SSID 会破坏 iPhone 的 wifi 功能。

令人欣慰的是，如果你的 iPhone 遇到了 it ，这个问题很容易解决:只需进入**设置>常规>重置**，选择**重置网络设置**。这将删除所有保存的 wifi 连接信息，因此下次重新连接到安全网络时，您必须建立一个新的连接，但它也会立即恢复错误。

虽然修复 wifi 漏洞很简单，但防止它却要复杂得多。

显然，避免将连接到网络，或者将您的家庭 wifi 命名为“%p%s%s%s%s%n ，如果您注意到公共 wifi 点使用该特定的 SSID，则向其他人发出警告。然而，正如我们在 [Gizmodo 的朋友指出的](https://gizmodo.com/don-t-connect-your-iphone-to-this-wifi-network-1847138276) ，有可能*其他*看似良性的网络 id 也会引发同样的故障。这使得 iPhone 用户容易被网络流氓、恶意用户，甚至是不知情的用户无意中给他们的公共 wifi 连接起了一个错误的名字。所以一般来说，一个会使名称中有很多“%”符号的网络无效，如果你在连接到公共网络后遇到错误，会通知网络管理员。如果这个漏洞足够普遍，苹果很可能会发布补丁来修复它。当然，这个问题也有可能无法解决——即使能够解决，每个用户也有责任同时保证自己设备的安全。

[ [9to5Mac](https://9to5mac.com/2021/06/19/a-specific-network-name-can-completely-disable-wi-fi-on-your-iphone/)