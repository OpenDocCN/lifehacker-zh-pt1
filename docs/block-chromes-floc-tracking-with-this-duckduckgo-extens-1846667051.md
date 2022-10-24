# 用这个 DuckDuckGo 扩展阻止 Chrome 的絮状物跟踪

> 原文：<https://lifehacker.com/block-chromes-floc-tracking-with-this-duckduckgo-extens-1846667051>

如果你可以浏览网页而不用担心你的行为和活动被跟踪、被转储到个人资料中、被卖给营销人员，这样他们就可以更有效地向你提供可能比其他东西更让你感兴趣的 T2 东西的广告，这不是很好吗？



虽然我们可能永远看不到那一天，但至少像 DuckDuckGo 这样的公司正在尽自己的一份力量来对抗最新最伟大的跟踪技术。在这种情况下，这是谷歌的决定推进[FLoC](https://blog.google/products/ads-commerce/2021-01-privacy-sandbox/)——duck duck go 非常不喜欢的东西，它现在正在为其 Chrome 扩展 添加反 FLoC 跟踪功能。如果你想在谷歌的房子里尽可能地限制跟踪，这是值得一试的。

### 什么絮状物？

如果你没听说过 FLoC，我不怪你。我不知道有多少人在他们的浏览器中不使用任何屏蔽软件；普通人不知道，也不关心他们是如何在网上被追踪的。

谷歌决定在 Chrome 中屏蔽第三方 cookies，转而转向基于 FLoC 的模型，或“群组联合学习”，其工作原理是这样的:不是被视为一个其浏览习惯(结合各种其他数据)可以用来在网上取消匿名的个人，而是一个更大的人群或群组中的无名个体，他们拥有相似的特征。

如 [Web 孵化器社区群的](https://wicg.io/) GitHub 页面对絮 [描述](https://github.com/WICG/floc) :

> 浏览器使用机器学习算法，根据个人访问的网站开发群组。这些算法可能基于被访问网站的 URL、这些页面的内容或其他因素。核心思想是，算法的这些输入特征，包括网页历史，都保存在浏览器的本地，而不是上传到其他地方——浏览器只暴露生成的群组。浏览器确保群组分布均匀，这样每个群组代表数千人。浏览器可以进一步利用其他匿名方法，例如差分隐私。群组的数量应该很少，以强调它们无法携带详细信息——短群组名称(“43A7”)有助于说明这一点。”

cFLoC 的批评者认为这项技术制造了与它试图解决的一样多的隐私问题:从当用户的信息(隐藏在群组中)突然与识别特征(如登录)联系在一起时会发生什么，到由于能够在网络上以不同的方式针对不同的人群而产生的普遍歧视问题。正如 EFF 的贝内特·塞普斯 [所写的](https://www.eff.org/deeplinks/2021/03/googles-floc-terrible-idea) :

> 即使拥有绝对的权力来决定哪些信息可以被用来针对谁，平台也常常无法防止他们的技术被滥用。但是 FLoC 将使用一种无监督的算法来创建它的集群。这意味着没有人能直接控制人们是如何组合在一起的。理想情况下(对广告商而言)，FLoC 将创建具有有意义的行为和共同兴趣的群体。但是网上行为与各种敏感特征相关——人口统计学特征，如性别、种族、年龄和收入；”大 5”人格特质；甚至心理健康。很有可能 FLoC 也会沿着这些轴对用户进行分组。FLoC 分组也可能直接反映对与药物滥用、经济困难或对创伤幸存者的支持有关的网站的访问。

这个问题的理想解决方案是完全消除跟踪——没有第三方 cookies，没有指纹，没有队列，什么都没有。实际上，你将不得不自己发动这场战斗，因为像谷歌这样的公司在迎合中间路线方面有既得利益(或者，除此之外，对广告客户更友好一点，，因为这有助于保持光明)。

这就是 DuckDuckGo 的扩展发挥作用的地方。由于 Chrome 是目前唯一使用 FLoC 的浏览器——更确切地说，*将*使用 FLoC(目前正在测试)——你所要做的就是做一些调整，让自己远离追踪技术。如果安装一个扩展太麻烦，DuckDuckGo 指出你可以尝试一些其他的技术来禁用 FLoC(目前):

> *   *Keep logging out of your Google account;*
> *   [*Do not use Chrome*](https://support.google.com/chrome/answer/185277) *or* [*to create synchronization password*](https://support.google.com/chrome/answer/165139?co=GENIE.Platform%3DAndroid&hl=en#zippy=%2Ccreate-a-passphrase) *;*
> *   *In* [*Google Activity Control*](https://myaccount.google.com/activitycontrols) *, disable "Web & application activity" or "including Chrome history and activities from websites, applications and devices using Google services"*
> *   *Disable "advertising personalization" in* [*Google advertising settings*](https://adssettings.google.com/) *or "also use your activity information from Google services & to personalize advertisements on websites and applications that cooperate with Google to display advertisements."* T46】T47】

我不是 DuckDuckGo 的超级用户，但我不能指责该公司在这一点上的评估。然后是整个“ [”谷歌测试 FLoC](https://blog.malwarebytes.com/cybercrime/privacy/2021/04/millions-of-chrome-users-quietly-added-to-googles-floc-pilot/) 没有要求用户选择进入试用“方面，这也让我有点不知所措，隐私方面。(禁用所有第三方 cookies 到 [选择退出 FLoC 试用](https://amifloced.org/) ，如果你注册了——t 尽管这可能会破坏你的网络体验，所以你可能暂时最好使用完全不同的浏览器。)

我不认为未来会是没有絮状物的，但是如果你是 Chrome 的粉丝，你至少可以让自己稳定下来，迎接下一次对你隐私的大冲击。而且我迫不及待地想有人做一个扩展，告诉你你正在访问的网站是利用 FLoC *还是*选择退出。