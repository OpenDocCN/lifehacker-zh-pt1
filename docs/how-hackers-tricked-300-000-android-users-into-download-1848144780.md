# 黑客如何诱骗30万安卓用户下载窃取密码的恶意软件

> 原文:[https://life hacker . com/how-hackers-tricked-300-000-Android-users-into-download-1848144780](https://lifehacker.com/how-hackers-tricked-300-000-android-users-into-download-1848144780)

网络安全公司ThreatFabric最近的一份报告显示， [超过30万安卓用户安装了木马程序](https://www.threatfabric.com/blogs/deceive-the-heavens-to-cross-the-sea.html) ，秘密窃取他们的银行信息。虽然这些应用已经被谷歌删除和停用，但开发者使用了独特的方法来部署恶意软件，所有Android用户都需要警惕。

Watch

## 黑客使用了多种类型的恶意软件

ThreatFabric的报告只提到了几个恶意应用，但它们包括QR扫描仪、PDF扫描仪、健身追踪器和加密应用。与其他虚假宣传其功能的虚假应用不同，这批恶意Android软件中的许多应用都按预期工作。但在幕后，这些应用正在窃取密码和其他用户数据。

研究人员根据所使用的特定恶意软件将应用程序分为四个独立的“家族”:

*   **Anatsa:** 四大恶意软件家族中最大的一个，拥有超过200，000次的总下载量，它使用了一种名为Anatsa的银行特洛伊木马。木马利用安卓的截屏辅助功能窃取登录信息等个人数据。

*   **外星人*:*T3】下载量第二大的木马是外星人，安装在超过95000台设备上。Alien拦截了双因素认证(2FA)代码，黑客可以使用这些代码登录用户的银行账户。**
*   **Hydra和Ermac:** 后两个家族使用了Hydra和Ermac恶意软件，这两个软件都与Brunhilda网络犯罪组织有关联。该组织利用该恶意软件远程访问用户设备，窃取银行信息。ThreatFabric的报告称，使用Hyrda和Ermac的应用程序累计下载量超过15000次。

## 这些恶意软件家族如何绕开谷歌的安全措施

ThreatFabric向谷歌报告了这些应用，此后它们已从Play Store中移除，并在安装它们的任何设备上被停用。但真正的问题是黑客如何设法将恶意软件偷偷放入应用程序中。

通常情况下，Play Store会捕捉并删除带有可疑代码的应用程序。然而，在这些情况下，恶意软件并没有在最初的下载中发布，而是被添加到用户必须安装才能继续运行应用程序的更新中。使用这种方法，开发者可以提交他们的应用程序，而不会被谷歌检测到。由于应用程序按预期运行，用户不太可能注意到任何问题。然而，也有一些迹象表明，这些有问题的更新是有问题的，因为它们可能要求可访问性服务权限或强迫用户下载额外的软件。

## 如何保护你的安卓设备免受恶意软件的侵害

你可以做一些事情来保护你的设备和数据免受类似恶意软件的攻击。首先，始终 [关注应用程序请求的权限](https://lifehacker.com/use-permissions-to-keep-scammy-apps-off-your-android-1843026818)——不仅仅是第一次安装时，而是每次运行或更新时。如果应用程序有任何可疑或不必要的行为，请删除并报告。例如，二维码扫描仪没有理由需要访问您的无障碍服务。

同样，只从谷歌Play商店直接安装更新。如果一个应用程序说它需要突然更新，但你在Play Store应用程序中没有看到，它可能不是一个合法的补丁。同样的道理也适用于随机下载额外应用程序的请求:下载应用程序唯一安全的时候是当你自己从可信的、经过验证的来源下载APK文件的时候，比如APK镜报或者XDA发展论坛。不要忘记在下载 之前彻底审查一个应用程序，即使是在Google Play上，因为黑客可以通过误导性的评论来伪造应用程序的合法性。

虽然这些策略不能保证防止所有恶意软件攻击，但如果你将它们与其他网络安全实践结合起来，如使用由 [加密密码管理器](https://lifehacker.com/advisor/best-password-manager/) 、 [2FA登录](https://lifehacker.com/no-one-knows-about-two-factor-authentication-and-privat-1838913065) 和 [可靠的反恶意软件和防病毒应用](https://lifehacker.com/use-these-antivirus-and-anti-malware-apps-instead-of-av-1841264690) ，你将在未来更好地抵御不良行为者和不良应用。

[ [ZDNet](https://www.zdnet.com/article/over-300000-android-users-have-downloaded-these-banking-trojan-malware-apps-say-security-researchers/?ftag=COS-05-10aaa0g&taid=61a631ec9a8dbd0001051986&utm_campaign=trueAnthem%3A+Trending+Content&utm_medium=trueAnthem&utm_source=twitter)