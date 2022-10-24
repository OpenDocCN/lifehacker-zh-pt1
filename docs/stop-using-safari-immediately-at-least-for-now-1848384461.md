# 立即停止使用 Safari(至少目前如此)

> 原文：<https://lifehacker.com/stop-using-safari-immediately-at-least-for-now-1848384461>

尽管最近有一些负面报道称 AirTags 彻底改变了跟踪行业，但在隐私和安全方面，苹果公司比其他大型科技公司有着良好的声誉。了解了这一点，你可能会惊讶地发现，苹果自己的网络浏览器 Safari 现在在该公司的任何平台上使用都不安全，包括 Mac、iOS 和 iPadOS。

Watch

一个严重的 Safari 问题可能会使您的一些 Google 帐户数据和浏览历史记录因 IndexedDB 实现错误而被窃取。当您正常访问一个网站时，该网站应该只能访问由其自己的域名创建的任何数据库。然而，这个漏洞允许网站查看其他数据库，并从这些数据库中搜集信息，如你的谷歌账户头像、个人数据或浏览历史。

**注:苹果此后用 iOS 15.3、iPadOS 15.3、macOS 12.2 修补了这个 bug。** [**点击此处了解更多**](https://lifehacker.com/update-safari-immediately-1848426551?rev=1643223490809) **。**

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-Z7dPeGpCl8s&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-Z7dPeGpCl8s&start=0) 

使用 FingerprintJS 的测试站点 [Safari Leaks](https://safarileaks.com) ，可以看到这个问题在起作用。当你在 Safari 中打开它时，该网站可能会立即获取你的谷歌用户 ID。即使它不能，你也可以在一个新的标签页中打开它的任何一个测试网站，并返回到 Safari Leaks 查看几乎立即报告的浏览历史。如果 Safari 正常工作，Safari Leaks 将无法访问这种类型的信息，因为该网站只能访问其域创建的数据库中的数据。但它可以从阿里巴巴、Instagram、Twitter 以及其他可能使用 IndexedDB JavaScript API 的网站上抓取信息。

FingerprintJS 是第一个报告 漏洞的，但是它在 1 月 14 日的博客文章并不是第一次公开漏洞。根据 FingerprintJS 的说法，这个问题是在去年 11 月 28 日发布到 WebKit Bug Tracker 上的——但直到 1 月 16 日周日，苹果才开始开发补丁，这意味着该漏洞至少在过去七周内一直没有得到处理。

现在， [苹果官方正在为这个安全漏洞](https://9to5mac.com/2022/01/18/apple-working-on-a-fix-for-safari-bug-that-leaks-browsing-history-and-google-id/) 开发补丁，但是在补丁出来之前，Safari 仍然容易受到攻击。

## 如何应对这一 Safari 安全威胁

如果你用的是 Mac，一个简单的解决方法就是使用另一个浏览器。Chrome，Firefox，Edge，Opera，随你挑。不幸的是，对于我们这些使用 iOS 和 iPadOS 的人来说，情况就不一样了。虽然你会在 App Store 上找到这些浏览器，但它们实际上并不是你在 Mac 上使用的浏览器。

苹果，作为苹果，不会让开发者为 iPhone 和 iPad 开发自己的成熟浏览器。相反，开发者可以将他们的浏览器功能添加到 Safari 中，并作为一个独立的浏览器“出售”。虽然 iOS 上的 Chrome 看起来像是桌面浏览器的移动版本，但它实际上是顶部带有谷歌皮肤的 Safari 浏览器。当然，你可以使用方便的功能，如 Mac 和 iPhone 上的 Chrome 之间的数据同步，但你在移动设备上使用的实际上是苹果的核心。

通常情况下，这不是什么大不了的事情(尽管这很烦人)。然而，由于安全问题，你不能像在 Mac 上那样更换你的浏览器。在苹果发布其三大平台的 Safari 补丁之前，无论你使用哪种“浏览器”,在 iPhone 或 iPad 上使用互联网都是有风险的。

1 月 26 日星期三，这篇文章更新了，包含了苹果针对 Safari 漏洞的安全补丁的信息。

[ [9to5Mac](https://9to5mac.com/2022/01/18/apple-working-on-a-fix-for-safari-bug-that-leaks-browsing-history-and-google-id/)