# 如何使用iCloud“私人中继”对广告追踪器隐藏您的浏览历史

> 原文:[https://life hacker . com/how-to-hide-your-browsing-history-from-ad-trackers-with-1847553318](https://lifehacker.com/how-to-hide-your-browsing-history-from-ad-trackers-with-1847553318)

随着 [iOS 15](https://lifehacker.com/the-10-coolest-ios-15-features-announced-at-wwdc-2021-1847048865) 、iPadOS 15、macOS Monterey的更新，苹果正在自动将所有iCloud付费计划升级到iCloud+。如果你为iCloud storage付费，你现在可以访问私人中继功能，并能够在线隐藏你的电子邮件地址。

Watch

## iCloud私有中继是如何工作的？

先明确一点: iCloud Private Relay不是VPN，对第三方app不起作用。它*将*做的是保护通过你的iPhone、iPad或Mac上的Safari浏览器的流量。

在某种程度上，私有中继比第三方VPN更安全。当你在Safari中访问一个网站时，数据首先会被发送到Apple，Apple会删除所有个人标识符(比如你的IP地址)。然后，I t被发送到一个辅助服务器(由第三方维护)，在那里你被分配一个新的、临时IP地址，用于你正在访问的网站。这阻止广告追踪器和cookies收集你的个人数据。

苹果使用这个两步过程来确保没有任何一个实体(无论是苹果还是第三方服务器)可以跟踪你。苹果只知道你的IP地址，第三方只知道你正在访问的网站，所以两者都不知道全貌。当你在 [使用不可信的 VPN](https://lifehacker.com/how-to-find-a-trustworthy-vpn-1833045522) 时，这通常是一种风险。

就可用性而言，私有中继的表现不像VPN。例如，没有选择你的位置的选项；苹果仍将使用离你最近的服务器，在你自己的国家。你可以切换到“保持大致位置”模式，给出一个在你所在区域周围*的位置，但不给出具体位置。这意味着你将无法使用私人转播从另一个国家观看网飞，或者解除你所在地区的地理限制网站的封锁。*

## 如何启用iCloud私人中继

如果你已经为iCloud计划付费，私人中继功能绝对是一个不错的选择。下面介绍如何启用它。

O 在你的iPhone或iPad上，打开**设置**应用程序，点击顶部的你的个人资料。点击**I cloud**部分，选择**私有中继**选项。现在，点击“**专用继电器**”选项旁边的开关，启用该功能。

如果您想更改您的 IP地址设置，请选择“ **IP地址位置**”选项，并切换到“**使用国家和时区**”选项，以切换到您所在国家的任何更广阔的位置。

你也可以在你的Mac上启用这个功能，前提是你运行的是macOS Monterey。打开“**系统偏好设置**app，进入“ **Apple ID** 板块。选择“ **iCloud** ”，然后启用“**私有中继**功能。