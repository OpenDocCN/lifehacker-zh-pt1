# 如何将密码从 iCloud 钥匙串导入和导出到其他密码管理器

> 原文：<https://lifehacker.com/how-to-import-and-export-passwords-from-icloud-keychain-1847962074>

iCloud Keychain 一直有点像一个孤岛:一个隐藏的、安全的天堂，只要你留在苹果严格的生态系统内。要访问和添加密码，你*必须*使用 Safari，而且没有可靠的方法导出密码。但慢慢地，iCloud Keychain(或 iCloud 密码)变得不那么像围墙花园了。

Watch

例如，你现在可以在 Windows 电脑 上使用 [iCloud 密码，包括第三方浏览器。在 macOS Monterey 中，Apple 添加了一个简单、通用的 CSV(纯文本、未加密)导入和导出功能，该功能在其他密码管理器中得到广泛支持，如 Bitwarden、LastPass 和 1Passwords。这一更改意味着现在可以根据您的需要更容易地移入和移出 iCloud 钥匙串。它是这样工作的。](https://lifehacker.com/how-to-finally-use-your-icloud-passwords-on-windows-1847507307)

## 如何在 iCloud 钥匙串中导入密码

如果您已经准备好了一个 CSV 文件，您可以导入现有的用户名和密码数据库。这是一种标准格式，它将数据存储在一个纯文本的未加密数据库中，当您从浏览器(如 Chrome)或密码管理器(如 LastPass)中导出密码时，就会得到这种格式。

首先，进入**系统** **偏好设置** > **密码**(苹果通过其 [macOS Monterey 更新](https://lifehacker.com/31-new-macos-monterey-features-youll-actually-want-to-u-1847900965) 将密码部分移至系统偏好设置)并进行认证，以查看您所有用户名和密码的列表。点击底部工具栏的三点**菜单**按钮，选择“**导入密码**选项。

选择 CSV 文件，点击**导入**按钮。

您将被要求使用您的密码或触控 ID 进行鉴定。完成后，密码将被导入到您的 iCloud 钥匙串中。该过程完成后，Apple 会很有帮助地询问您是否要删除原始 CSV 文件。

我们建议您选择“**删除**”选项，因为它会将文件从您的本地存储中删除，同时也会删除回收站。如果你不删除文件，任何拿到它的人都会知道你所有的用户名和密码(你还应该对你所有的重要账户使用 [双因素认证](https://lifehacker.com/no-one-knows-about-two-factor-authentication-and-privat-1838913065) )。没有办法恢复这个文件。

## 如何从 iCloud 钥匙串导出密码

想要从 iCloud 钥匙串转移到更专业的密码管理器吗？这终于容易做到了。进入**系统偏好设置** > **密码**，使用您的管理员密码或触控 ID 进行验证。然后点击底部工具栏的三点**菜单**按钮，选择“**导出密码**选项。

从弹出菜单中，点击“**导出密码**”

选择位置，点击**保存**按钮。

使用您的管理员密码或触控 ID 进行身份验证。现在，您的所有密码都将导出到该位置。如上所述，在您选择的密码管理器中导入数据后，不要忘记删除 CSV 文件。

## 你现在应该带着你的密码去哪里？

有了这个包含您所有用户名和密码的 CSV 文件，您可以去任何您想去的地方。您可以尝试任何密码管理器或浏览器与您的所有个人数据。

但是现在有很多选择。你应该为 1 密码 付费吗？LastPass 还值得吗？在我们的测试中，我们只发现了一个 iCloud 密码的真正竞争者， [那就是 Bitwarden](https://lifehacker.com/bitwarden-is-now-the-best-free-alternative-to-lastpass-1846289833) ，因为他们的免费计划对大多数用户来说绰绰有余。它使用最先进的加密技术，其基本应用程序是开源的，因此任何人都可以审计其安全措施。此外，它拥有强大的应用程序和浏览器扩展，几乎随处可见。只需点击一下，你就可以 [将 CSV 文件导入到 Bitwarden](https://bitwarden.com/help/article/import-data/#:~:text=Import%20to%20your%20Personal%20Vault,-Importing%20data%20to&text=To%20import%20your%20data%3A,Bitwarden%20support%20for%20import%3F).) 中，所以，如果这个管理器听起来适合你，不妨试一试。

*关于 G/O Media 合作伙伴的密码管理器的更多信息:*
*-* [*回顾最佳密码管理器*](https://lifehacker.com/advisor/best-password-manager/)
*-*[*1 password:it 所提供的内容*](https://lifehacker.com/advisor/1password-review/)
*-*[*LastPass:it 所提供的内容*](https://lifehacker.com/advisor/lastpass-review/)

Lifehacker 并不参与这些文章的创作，但可能会从购买其内容中获得佣金。