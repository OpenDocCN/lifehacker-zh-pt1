# 这些流行的 Android 应用程序将用户数据置于风险之中

> 原文：<https://lifehacker.com/these-popular-android-apps-are-putting-user-data-at-ris-1846943271>

根据 Check Point Research 的一份 [报告，由于第三方服务的不安全，许多流行的 Android 应用程序将你的个人数据置于风险之中。](https://research.checkpoint.com/2021/mobile-app-developers-misconfiguration-of-third-party-services-leave-personal-data-of-over-100-million-exposed/) 

Watch

该报告强调了影响 Google Play 上 23 个不同应用程序的几个不同的安全缺陷，每个应用程序的下载量从 5 万到 1000 万不等。大多数违规应用使用不安全的实时数据库和云存储服务来收集和存储用户信息、开发人员数据和公司内部资源。安全研究人员能够从 13 个应用程序中找到不安全的云数据库，这意味着外部参与者也可以*和*访问它们。

其他应用程序错误地配置了推送通知管理器，黑客可以利用这些管理器来拦截和修改来自开发者的看似合法的通知，向它们植入恶意软件、钓鱼链接或误导性内容。

这些漏洞使至少 1 亿 Android 用户面临欺诈、身份盗窃和恶意软件攻击的风险。

## 哪些 Android 应用程序将您的数据置于风险之中？

Check Point Research 表示，它在 23 个应用程序中发现了一个或多个这样的缺陷，其中 13 个应用程序拥有可公开访问的实时数据库。然而，该报告仅列出了其中五个应用的名称:

*   **Astro Guru:** 下载量过千万的星座 app。它存储了每个用户的全名、出生日期、性别、GPS 位置、电子邮件地址和支付信息。
*   **iFax:** 一个移动传真应用程序，它将的 50 多万用户发送的所有文档存储在一个可访问的云数据库中——云存储密钥嵌入在应用程序中。
*   **Logo Maker:** 一款拥有超过 17 万用户的平面设计 app。Check Point 发现所有用户的全名、帐号 id、电子邮件和密码都是可以访问的。
*   **截屏:**这款应用的下载量超过 1000 万次。报告显示将账户密码保存在存储该应用程序所做记录的同一个云服务上，使他们容易受到攻击。
*   **T'Leva:** 安哥拉的一款打车应用，下载量超过 50，000 次，这款可以留下司机和乘客之间的文本历史、位置数据、全名和电话号码。

Check Point 表示，它通知了应用程序的创建者，但只有 Astro Guru 做出了回应，所有应用程序仍可在 Google Play 上使用。

## wAndroid 用户应该做些什么来保证他们的数据安全？

第一步是停止使用 Check Point Research 的报告中提到的应用——但由于只有五个被点名，这意味着至少有 18 个其他应用在没有适当保护的情况下存储你的数据。

这只是我们从 Check Point 的报告中了解到的情况——很可能有*多得多的*应用程序、网站和服务的数据库配置有误，只有在泄露后我们才会知道。

虽然 Check Point Research 的报告和其他类似的报告可以提醒开发人员注意不安全的数据存储做法，但最终还是要由开发人员来解决这个问题。然而，用户可以采取预防措施来保护他们的个人信息和其他重要数据的安全，无论他们使用什么应用程序:

1.  尽可能使用 [双因素认证](https://lifehacker.com/update-your-password-whenever-you-get-a-random-2fa-requ-1844571471) (2FA)。
2.  从你的账户中保留个人信息(例如，如果某项服务不需要，就不要添加你的家庭地址)，或者尽可能使用虚假信息。
3.  为每个账户创建唯一的密码 [使用加密的密码管理器](https://lifehacker.com/how-to-get-started-with-a-password-manager-1846890484) 。
4.  如果可以的话，不要链接像谷歌、脸书和推特这样的第三方账户。
5.  将 [app 权限保持到最低](https://lifehacker.com/use-permissions-to-keep-scammy-apps-off-your-android-1843026818) 。
6.  使用 [服务，通知您](https://lifehacker.com/10-billion-wrecked-accounts-show-why-you-need-have-i-be-1836996930) 帐户遭到破坏。

这些额外的步骤不会阻止违规行为，但它们可以降低身份盗窃、欺诈和其他骗局的风险。我们还有预防和 [响应数据泄露](https://twocents.lifehacker.com/what-to-do-if-theres-a-data-breach-1826450129) 、 [勒索软件](https://lifehacker.com/why-you-should-use-windows-defenders-ransomware-prevent-1837311176) 攻击、 [恶意软件](https://lifehacker.com/how-to-avoid-the-new-astaroth-malware-thats-hitting-win-1842509944) 、 [身份盗窃](https://lifehacker.com/how-to-tell-if-youre-the-victim-of-a-sim-swapping-attac-1841000917) ，以及如何识别常见的 [网络钓鱼战术和其他网络诈骗](https://lifehacker.com/the-complete-guide-to-avoiding-online-scams-for-your-l-5420356) 的指南。

[ [威胁帖](https://threatpost.com/100m-android-users-cloud-leaks/166372/)