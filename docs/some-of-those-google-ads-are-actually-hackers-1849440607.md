# 一些谷歌广告实际上是黑客

> 原文：<https://lifehacker.com/some-of-those-google-ads-are-actually-hackers-1849440607>

广告可能很烦人，但这也是谷歌不会在你每次搜索时向你收费的原因。有时候，它们甚至很有帮助:如果你搜索一个特定的产品，谷歌广告会把它的网站作为第一个结果呈现给你，你会很快到达你需要的地方。然而，最近，你最好跳过谷歌扔给你的任何广告:研究人员在该平台上发现了虚假广告，乍一看，就像真的一样。



这被称为“恶意广告”(一个可怕问题的伟大名称):坏演员将恶意软件注入虚假广告，希望用户会相信广告是合法的。你可能认为关于广告的一切都是合法的，甚至是网站的网址，但是当你点击它时，你面对的是一个骗局，而不是你期望访问的网站。

malware bytes Threat Intelligence[上个月在一条推文中首次用虚假的谷歌广告](https://twitter.com/MBThreatIntel/status/1549802054230482944) 强调了这个问题。他们开始在谷歌上搜索“YouTube”，这是一个简单的请求，应该可以提供一条通往视频服务的直接路径(毕竟谷歌拥有它，)。然而，谷歌并没有在搜索结果的顶部提供一个标准的 YouTube 链接，而是为该网站提供了一个*广告*。

乍一看，这个广告似乎是合法的，尤其是因为 URL 是正确的(https://www.youtube.com)。为什么*不会*链接带你去 YouTube？然而，当点击时，事情变得非常糟糕:来自“Windows Defender”的警报声称该网站被阻止“由于可疑的活动”，引用了木马间谍软件问题，并联系技术支持寻求解决方案。

得知这个警告*不是* Windows Defender，并且“技术支持”是不合法的，这可能并不令人惊讶: [根据 bleeding computer](https://www.bleepingcomputer.com/news/security/convincing-youtube-google-ads-lead-to-windows-support-scams/)的说法，如果你联系“技术支持”，他们会指示你将 TeamViewer 下载到你的计算机上，以便远程为你解决问题。由于 TeamViewer 允许另一个用户完全控制您的计算机，恶意用户很可能会使用该软件来对付您，要么将您锁定在计算机之外并索要赎金，要么窃取您的信息。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1549802054230482944&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1549802054230482944&autosize=1) 

在这个时候，谷歌搜索 YouTube 不会弹出这个恶意广告，或者根本没有任何广告，所以至少这种特殊情况是固定的。但这并不意味着所有其他的负面影响都被压制了。在任何谷歌搜索中，出现在典型搜索结果上方的广告都有可能是恶意的，用户只有点击它们才能知道。

## 如何远离虚假的谷歌广告

那么，你最好的选择就是完全避开谷歌广告。这真的不是一个高要求——通常，出现在广告下方的官方搜索结果就是你完成查询所需的全部。这也是谷歌可以用来追踪你兴趣的一个少广告。

如果你确实需要点击一个广告，有一些微妙的迹象需要注意:如果你看 Malwarebyte 的推文，结果是“YouTube -官方网站”YouTube 的一个合法结果只显示了它的名。此外，标题下面的文字看起来有点偏离，好像是从 YouTube 视频的描述中抽出来的。真正的结果并没有做到这一点，而是提供了 YouTube 作为一个平台的快速总结。

当然，如果黑客很狡猾，创造了一个真正有说服力的广告，最后一招是:如果广告把你带到了你想去的网站之外的地方，关闭窗口。不要遵循任何“警报”的指示，不要安装任何软件，只是 GTFO。点击广告本身可能不会伤害你的电脑，但安装恶意软件或允许黑客通过像 TeamViewer 这样的程序远程访问你的电脑会。

[ [哔哔声电脑](https://www.bleepingcomputer.com/news/security/convincing-youtube-google-ads-lead-to-windows-support-scams/)