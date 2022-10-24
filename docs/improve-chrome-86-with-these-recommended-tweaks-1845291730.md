# 用这些推荐的调整改进Chrome 86

> 原文:[https://life hacker . com/improve-chrome-86-with-these-recommended-tweaks-1845291730](https://lifehacker.com/improve-chrome-86-with-these-recommended-tweaks-1845291730)

我喜欢新的浏览器更新到来的时候，因为看到哪些被谈论的功能是活的，哪些需要一点*哄骗*才能出现总是很有趣。谷歌最近推出的Chrome 86就是这样的例子，该产品于昨日向所有人推出。

Watch

至少，我希望如此；直到一天快结束的时候，我才获得桌面浏览器的官方更新(通过关于谷歌Chrome浏览器的**帮助>)。然而，我现在有了Chrome 86，当你更新*你的*浏览器时，这里有你想知道的主要功能——包括我们对其他调整、附加功能的建议，以及除了谷歌新的Chrome goodies之外你想做的配置更改。**

* * *

### 使用后台节流来管理选项卡的效果

升级到Chrome 86的最好理由之一是其新的后台节流功能，该功能有望将你没有看到的所有标签的最大负载减少到你CPU的百分之一。这些选项卡必须处于非活动状态至少五分钟，限制才会生效。

**Lifehacker的建议:**我会将这个功能——一旦你更新到Chrome 86就会自动打开——与另一个 [插件](https://chrome.google.com/webstore/detail/the-great-discarder/jlipbpadkjcklpeiajndiijbeieicbdh?hl=en) ( [或两个](https://chrome.google.com/webstore/detail/the-great-suspender/klbibkeccnjlkjkiokjodocebajanakg) )结合起来，尽可能地从你的标签中节省内存。你甚至可以使用像 [OneTab](https://chrome.google.com/webstore/detail/onetab/chphlpgkkbolifaimnlloiipkdnihall?hl=en) 这样的插件来尽可能减少你的杂乱。当你需要时，Chrome的节流是一个有用的调整，但你不应该让它成为你对标签管理懒惰的入场券(他盯着他浏览器中的30多个标签说道)。

* * *

### 检查你蹩脚的Chrome密码，看看它们是否正常

如果你使用Chrome的密码管理器——至少你应该使用它来管理你复杂而独特的密码——那么一个全新的选项将让你快速检查以确保你保存的任何东西都没有被泄露。访问 **Chrome的设置>你和Google >密码>检查密码**就可以上手了。如果Chrome发现一个不安全的登录，它甚至会提示你通过点击一个按钮来改变它，这个按钮会直接把你带到一个网站的“密码重置”页面。(那得看网站是否设置了这个 [知名网址](https://w3c.github.io/webappsec-change-password-url) 功能。)

此外，Chrome的密码检查功能*应该*可以在Android和iOS上使用。如果你在设置中看不到它们，你可以启用`chrome://flags/#password-check`(同时，也可以启用`chrome://flags/#safety-check-android`或`chrome://flags/#safety-check-ios`。

**Lifehacker推荐:**所以，我一般不会用Chrome的密码管理器，因为我绝对热爱 [1Password](https://lifehacker.com/the-five-best-password-managers-5529133) 。我将继续使用1Password，因为我认为它的警告能力比Chrome强得多。举个例子:我在Chrome上输入了一些旧密码，我知道这些密码已经在网上泄露了，Chrome认为它们完全没问题。1然而，Password将这些标记为易受攻击(并注意到它们在某处遇到了一些数据泄露)，并敦促我更改它们。

这是一个小例子，但我认为专用的密码管理器更全面。也更贵，但密码安全是值得每月花几块钱的一件事；您可以少喝一杯咖啡或吃一份玉米煎饼，为您最重要的数字信息提供保险库般的保护。如果你没有别的东西，就使用Chrome，但不要认为它的密码管理器是完全准确的。更大的细分更有价值，比如1Password的(是的，我会设法改变这些。):

* * *

### 尽可能使用HTTPS

你的大部分网页浏览是在HTTPS网站上完成的， [而不是HTTP网站](https://transparencyreport.google.com/https/overview?hl=en) ，但这并不意味着我们应该对使用不太安全、未加密的网站放松警惕。有时候，如果一个网站很模糊，你真的没有选择。然而，我敢打赌，大多数人不会看着浏览器地址栏旁边小小的“锁”图标来检查你是否在HTTP或HTTPS上；你可能忘了它还在那里。

从Chrome 86开始，无论何时你想通过HTTP连接发送信息，浏览器都会提醒你。是的，即使表单本身出现在HTTPS网站上，这种情况也会发生。这个警告再明显不过了，正如谷歌在一篇博文 中强调的 [:](https://blog.chromium.org/2020/08/protecting-google-chrome-users-from.html)

**Lifehacker建议:**尽可能使用HTTPS，防止网站混合内容(使用通过HTTP和HTTPS在同一页面加载的内容)时的各种中间人攻击和其他诡计。如果你想了解更多，著名的安全研究员特洛伊·亨特有一个更好的解释:

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-nm-85-bDP6c&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-nm-85-bDP6c&start=0) 

尽管你现在可能不需要这个功能，但在你的浏览器中安装这个 [**HTTPS无处不在**](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp?hl=en) 扩展来确保你在任何可能的时候都使用首选的、安全的网站版本，这不会有什么坏处。如果你对在Chrome的地址栏中看不到“HTTP”或“HTTPS”感到恼火，你也可以编辑它们。访问此Chrome标志(通过将链接复制/粘贴到地址栏中)并将其设置为“禁用”以恢复它们:

`chrome://flags/#omnibox-ui-hide-steady-state-url-path-query-and-ref-on-interaction`

* * *

### 使用后退/前进缓存加快浏览速度

早在Chrome 79中，谷歌在浏览器中加入了一个有趣的小标志，允许你启用新的“后退/前进”缓存设置。正如谷歌的Addy Osmani在当时的 中写的 [:](https://developers.google.com/web/updates/2019/02/back-forward-cache)

> *“在Chrome团队中，我们正在探索一种新的* [***后退/前进缓存***](https://www.chromestatus.com/feature/5815270035685376) *以在用户导航离开时在内存中缓存页面(保留JavaScript & DOM状态)。这绝对不是一个微不足道的努力，但如果它成功了，它将使**来回导航**非常快。*
> 
> *后退/前进缓存(bfcache)在导航离开一个页面时缓存整个页面(包括JavaScript堆),以便当用户向后导航时可以恢复页面的完整状态。把它想象成当你离开时**暂停**一页，当你返回时**播放**一页。”*

**Lifehacker的建议:**假设该功能不会导致任何浏览器不稳定，奥斯马尼指出，启用它可以提高你的浏览性能高达19%。这对我们来说已经足够了，值得现在在Chrome(通过`chrome://flags/#back-forward-cache`标志)以及Chrome 86的Android版本中检查一下——该功能刚刚推出，可以使用相同的标志找到。

* * *

### Android:调整Chrome的“溢出”菜单

当你点击Android Chrome浏览器右上角的三点图标时，你会看到一个庞大而笨拙的选项菜单。这不是很优雅:

然而，你可以在这个菜单中添加图标*并通过启用Chrome 86中的两个标志
来对其内容进行分组*

*   `chrome://flags/#tabbed-app-overflow-menu-icons`
*   `chrome://flags/#tabbed-app-overflow-menu-regroup`

这些将难看菜单变成了可爱的新外观:

**Lifehacker的推荐:**做吧。为什么不呢？