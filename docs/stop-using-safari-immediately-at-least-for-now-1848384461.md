# 立即停止使用Safari(至少目前如此)

> 原文:[https://life hacker . com/stop-using-safari-immediately-至少现在-1848384461](https://lifehacker.com/stop-using-safari-immediately-at-least-for-now-1848384461)

尽管最近有一些负面报道称AirTags彻底改变了跟踪行业，但在隐私和安全方面，苹果公司比其他大型科技公司有着良好的声誉。了解了这一点，你可能会惊讶地发现，苹果自己的网络浏览器Safari现在在该公司的任何平台上使用都不安全，包括Mac、iOS和iPadOS。

Watch

一个严重的Safari问题可能会使您的一些Google帐户数据和浏览历史记录因IndexedDB实现错误而被窃取。当您正常访问一个网站时，该网站应该只能访问由其自己的域名创建的任何数据库。然而，这个漏洞允许网站查看其他数据库，并从这些数据库中搜集信息，如你的谷歌账户头像、个人数据或浏览历史。

**注:苹果此后用iOS 15.3、iPadOS 15.3、macOS 12.2修补了这个bug。** [**点击此处了解更多**](https://lifehacker.com/update-safari-immediately-1848426551?rev=1643223490809) **。**

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-Z7dPeGpCl8s&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-Z7dPeGpCl8s&start=0) 

使用FingerprintJS的测试站点 [Safari Leaks](https://safarileaks.com) ，可以看到这个问题在起作用。当你在Safari中打开它时，该网站可能会立即获取你的谷歌用户ID。即使它不能，你也可以在一个新的标签页中打开它的任何一个测试网站，并返回到Safari Leaks查看几乎立即报告的浏览历史。如果Safari正常工作，Safari Leaks将无法访问这种类型的信息，因为该网站只能访问其域创建的数据库中的数据。但它可以从阿里巴巴、Instagram、Twitter以及其他可能使用IndexedDB JavaScript API的网站上抓取信息。

FingerprintJS是第一个报告 漏洞的，但是它在1月14日的博客文章并不是第一次公开漏洞。根据FingerprintJS的说法，这个问题是在去年11月28日发布到WebKit Bug Tracker上的——但直到1月16日周日，苹果才开始开发补丁，这意味着该漏洞至少在过去七周内一直没有得到处理。

现在， [苹果官方正在为这个安全漏洞](https://9to5mac.com/2022/01/18/apple-working-on-a-fix-for-safari-bug-that-leaks-browsing-history-and-google-id/) 开发补丁，但是在补丁出来之前，Safari仍然容易受到攻击。

## 如何应对这一Safari安全威胁

如果你用的是Mac，一个简单的解决方法就是使用另一个浏览器。Chrome，Firefox，Edge，Opera，随你挑。不幸的是，对于我们这些使用iOS和iPadOS的人来说，情况就不一样了。虽然你会在App Store上找到这些浏览器，但它们实际上并不是你在Mac上使用的浏览器。

苹果，作为苹果，不会让开发者为iPhone和iPad开发自己的成熟浏览器。相反，开发者可以将他们的浏览器功能添加到Safari中，并作为一个独立的浏览器“出售”。虽然iOS上的Chrome看起来像是桌面浏览器的移动版本，但它实际上是顶部带有谷歌皮肤的Safari浏览器。当然，你可以使用方便的功能，如Mac和iPhone上的Chrome之间的数据同步，但你在移动设备上使用的实际上是苹果的核心。

通常情况下，这不是什么大不了的事情(尽管这很烦人)。然而，由于安全问题，你不能像在Mac上那样更换你的浏览器。在苹果发布其三大平台的Safari补丁之前，无论你使用哪种“浏览器”,在iPhone或iPad上使用互联网都是有风险的。

1月26日星期三，这篇文章更新了，包含了苹果针对Safari漏洞的安全补丁的信息。

[ [9to5Mac](https://9to5mac.com/2022/01/18/apple-working-on-a-fix-for-safari-bug-that-leaks-browsing-history-and-google-id/)