# 用“黑光”扫描网站上烦人的数据追踪器

> 原文:[https://life hacker . com/scan-websites-for-friendly-data-trackers-with-black ligh-1845145994](https://lifehacker.com/scan-websites-for-annoying-data-trackers-with-blackligh-1845145994)

屏蔽网站追踪器很容易。几款 [热门网页浏览器](https://lifehacker.com/block-ads-and-tracking-with-vivaldis-new-built-in-brows-1843006826) 默认屏蔽广告和追踪器，还有大量的 [第三方app和浏览器插件](https://lifehacker.com/how-to-make-ublock-origin-even-better-at-ad-blocking-in-1839964889) 可以在需要的地方填补空白。但是你有没有想过，这些有用的工具到底在阻止什么？

Watch

为了在你访问网站之前就能简单地看到网站跟踪的所有内容，以及这些数据在哪里被共享，我们强烈建议你去看看MarkUp.org基于网络的“”工具。(你也可以通过第三方软件、浏览器拦截器或者 [专门配置的浏览器设置](https://lifehacker.com/block-javascript-in-your-browser-to-prevent-annoying-em-1843186321) 来获取这些信息，但是你必须先访问一个网站，然后他们才会对其进行分析。)

### 如何使用黑光

操作方法如下: [打开黑光页面](https://themarkup.org/blacklight) ，然后在“输入网址”栏输入网址，点击**“扫描站点”**

下面是 [网站在后台](https://themarkup.org/blacklight/2020/09/22/how-we-built-a-real-time-privacy-inspector) 做什么(匿名):

> Blacklight通过无头浏览器访问每个网站，运行由标记构建的定制软件。该软件通过执行七种不同的测试来监控该网站上的哪些脚本可能在监视用户，每种测试都调查一种特定的已知监视方法。

几分钟后，表格将显示结果。这包括:

*   一个网站有多少广告追踪器
*   Blacklight发现了多少第三方cookies
*   存在可以绕过cookie拦截器的跟踪器
*   会话跟踪
*   键盘记录
*   脸书社会追踪
*   谷歌分析

有关详细信息，请单击这些字段旁边的箭头。你也可以下载结果的存档文件，点击时间戳旁边的“了解更多”,查看扫描页面的截图。

在扫描结果下面，Blacklight还包括一个被扫描网站以前曾与之共享信息的已知公司列表。单击公司名称旁边的箭头，查看有关其合作关系的更多信息，包括收集数据的特定域。如果一个网站的隐私政策看起来可疑——或者你只是好奇——用黑光灯扫描一下，并使用页面底部的“看到一些令人担忧的东西”工具来报告任何可疑的事情。

也就是说，不要仅仅依靠Blacklight的测试结果来审查网站的隐私。

页面底部的免责声明称，“Blacklight的结果不应被视为特定网站潜在侵犯隐私的最终结论。相反，它们应该被视为一种初步的自动检查，需要进一步的调查才能做出明确的声明。”

基本上，这个工具可以让你很好地了解一个网站如何跟踪和分享你的数据，但它可能无法捕捉到一切。虽然扫描结果很有帮助，有时会令人惊讶，但最好将Blacklight与专注于隐私的浏览器 和 [其他追踪应用](https://lifehacker.com/tag/ad-blocking) 结合使用，以保护你的个人数据隐私。