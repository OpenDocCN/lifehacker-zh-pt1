# 你应该马上更新你的苹果设备

> 原文：<https://lifehacker.com/you-should-update-your-apple-devices-right-now-1848737318>

苹果公司昨天发布了 iPhone (iOS 15.4.1)、iPad (iPadOS 15.4.1)和 Mac (macOS 12.3.1)的新更新，根据发布说明，他们修复了一些跨平台的恼人错误，包括许多 iPhone 用户在 iOS 15.4 上遇到的电池耗尽问题。然而，苹果没有宣传这些更新还包括的重要安全补丁，你应该尽快安装它们。



这些更新解决了两个关键的安全缺陷。一个漏洞，CVE-2022-22675，存在于所有三个平台中，允许不良行为者在应用程序中以内核权限执行任意代码——本质上是让黑客在你的设备上运行他们想运行的任何代码。另一个漏洞 CVE-2022-22674 是 macOS 特有的，出现在英特尔图形驱动程序中。该漏洞允许应用程序读取您的内核内存。

苹果公司表示，它有报告称这两个漏洞可能已经在野外使用，因此这些更新尤为关键。

> **AppleAVD**
> 
> 适用于:macOS Monterey、iPhone 6s 和新款机型、iPad Pro(所有型号)、iPad Air 2 和新款机型、iPad 第 5 代和新款机型、iPad mini 4 和新款机型以及 iPod touch(第 7 代)

> 影响:应用程序可能能够以内核权限执行任意代码
> 
> 描述:通过改进边界检查解决了越界写入问题。苹果意识到有报道称该问题可能已被积极利用。
> 
> CVE-2022-22675:一位匿名的研究者
> 
> **英特尔图形驱动程序**
> 
> 适用于:马科斯蒙特雷
> 
> 影响:应用程序可能能够读取内核内存
> 
> 描述:越界读取问题可能导致内核内存泄漏，已通过改进的输入验证得到解决。苹果意识到有报道称该问题可能已被积极利用。
> 
> CVE-2022-22674:一位匿名研究员

也就是说，安全补丁并不是更新设备的唯一原因。对于 iPhone 和 iPad，这些更新包括对以下错误的修复:

> *   After updating to iOS 15.4/iPadOS 15.4, the battery may run out faster than expected.
> *   Braille devices may become unresponsive when navigating text or displaying warnings.
> *   Hearing AIDS made for iPhone/iPad may lose connection in some third-party applications.

Mac 用户可以期待对这两个错误的修复，其中一个将特别受游戏玩家欢迎:

> *   The USB-C or Thunderbolt external display does not turn on when connected to Mac mini (2018) as the second display.
> *   Bluetooth devices, such as game controllers, may be disconnected from your Mac after playing audio through some Beats headphones.

## 如何更新到 iOS 15.4.1、iPadOS 15.4.1、macOS 12.3.1

要将你的 iPhone 或 iPad 更新到 15.4.1，请前往**设置>常规>软件更新**。要将您的 Mac 更新到 macOS 12.3.1，请前往**系统偏好设置>软件更新**。如果您的设备上有更新，您将在此处看到。按照屏幕上的说明下载并安装软件，既保护自己免受这些安全缺陷的影响，又修复这些恼人的错误。