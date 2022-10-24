# Peloton 的数据泄露提醒人们尽可能地撒谎

> 原文：<https://lifehacker.com/pelotons-data-breach-is-a-reminder-to-lie-whenever-you-1846858363>

Peloton 遭遇了数据泄露。好消息是什么？关于你锻炼习惯的信息随后被外人随意获取，这并不那么糟糕。然而，Peloton 的延迟反应更令人担忧。

Watch

正如 [Pen Test Partners](https://www.pentestpartners.com/security-blog/tour-de-peloton-exposed-user-data/) 在最近的一篇博客文章中描述的那样，该公司以前使用的一些 API 可以被任何人查询——经过认证的*和*未经认证的用户都一样。该公司后来改变了这一做法，只允许前者，但鉴于任何对数据感兴趣的人都可以简单地注册一个免费的 Peloton 账户，这并没有多大的保护作用。

至于攻击者可以获得什么，可用的数据包括:

> *   *User id 【T1]*
> *   *coach id 【T1]*
> *   *Group Membership*
> *   *Location*
> *   *Exercise Statistics*
> *   *Gender and age*
> *   *Is a person in the studio*

这很烦人，但并不可怕。如果攻击者知道你的运动量，他们就没什么可做的了。但是*有可能*他们会利用这些信息(单独或结合其他数据泄露提供的其他信息)向您发送一个巧妙的网络钓鱼企图。

更令人不安的是，Peloton 花了多长时间才回应关于这些(普遍开放的)API 的报道。正如 Pen 测试合作伙伴所指出的:

> *   ***20 <sup>th</sup> January, 2021:** according to their [Vulnerability Disclosure Plan], it was privately disclosed to Peloton.*
> *   ***20th January 2021:** Receipt confirmation. This is the last time we heard from Peloton.*
> *   ***22 <sup>nd</sup> January 2021:** We request to update and provide help to copy the vulnerability. No response.*
> *   ***2 <sup>and</sup> February 2021:** The problem of unverified API endpoints has been quietly partially solved-user data **is now only available to all verified Peloton users** . Uh ...?*
> *   ***2 <sup>nd</sup> February 2021:** In view of the silent repair, we ask for an update. No response. 90 days later, we asked a trusted journalist to have a conversation with Peloton on our behalf.* T46】T47】

这名记者是 TechCrunch 自己的 [扎克·惠特克](https://techcrunch.com/2021/05/05/peloton-bug-account-data-leak/) ，他最终在 Peloton 上发表了一篇文章，而*最终*似乎得到了公司的关注，更重要的是，影响了改变。

作为一名安全/隐私爱好者，我发现看到事情发展到这一步令人沮丧。虽然 Peloton 声称，自最初提交漏洞以来，它一直在采取行动，但奇怪的是巧合的是，这些漏洞仍然是可利用的——实际上是可利用的——直到技术领域最大的出版物之一曝光了该问题。Peloton 尚未证实或否认数据*不是由外部团体*一起*从*搜集的，这越来越令人恼火。

这一整集应该让你把你的 Peloton 自行车扔进垃圾桶吗？不。那是一件昂贵的设备。然而，我会留意任何未来 Peloton 数据泄露的消息；你可能必须自己采取行动，而不是等待 Peloton 采取适当的披露措施(和补救措施)。您可能还想考虑尽可能模糊您的数据。如果这对你骑车(或慢跑)来说不是必需的，那么 Peloton 没有理由需要它——给他们一个假的生日、地址、姓名等等。你的竞争对手不会介意的。