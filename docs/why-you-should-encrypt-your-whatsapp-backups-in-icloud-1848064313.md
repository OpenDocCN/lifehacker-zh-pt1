# 为什么应该在 iCloud 中加密 WhatsApp 备份

> 原文：<https://lifehacker.com/why-you-should-encrypt-your-whatsapp-backups-in-icloud-1848064313>

拥有超过 20 亿活跃用户的 WhatsApp 是全球最受欢迎的消息应用之一，也是少数几个默认提供端到端加密的应用之一。这意味着除了你之外，没有人能看到你的对话。即使是 WhatsApp 也无法读取你的对话，因为它没有解密你聊天内容的密钥。



这都是真的，除了一个场景:备份到 iCloud 的 WhatsApp 聊天记录都是未加密的，所以如果有人拿到了你的 iCloud 备份，他们可以很容易地阅读你所有的信息。但是现在，WhatsApp 有了一个可选功能，使用密码或安全密钥，通过同样的双因素认证来保护你的 WhatsApp 备份。

## 如何通过 iCloud 为 WhatsApp 备份启用端到端加密

在我们开始之前，你应该知道 WhatsApp 端到端加密依赖于密码或 64 位安全密钥。如果您丢失了密码，您将无法恢复您的聊天记录，因此请确保您使用的是安全的且可识别的密码。如果你使用一些复杂的东西，请确保将其保存在你的密码管理器中(可以是 [iCloud 钥匙链](https://lifehacker.com/how-to-import-and-export-passwords-from-icloud-keychain-1847962074) 或类似 [Bitwarden](https://lifehacker.com/bitwarden-is-now-the-best-free-alternative-to-lastpass-1846289833) 的第三方服务)。

要开始使用，首先要将你的 WhatsApp 应用程序更新到最新版本。WhatsApp 正在慢慢向其 20 亿用户推出这一功能，所以如果你还没有看到，过几天再试一次。

打开 WhatsApp，从“**设置**选项卡，进入“**聊天**在这里，选择**聊天备份**，点击**端到端加密备份**按钮。点击“**打开**”按钮，从下一个屏幕中选择“**创建密码**”选项。

在这里，创建一个至少包含六个字符和一个字母的密码。然后，点击“**下一个**按钮。

一切设置完成后，点击“**创建**按钮，切换到端到端加密备份。给 WhatsApp 一些时间过渡到加密备份。

如果你想关闭这个功能，回到**设置** > **聊天** > **聊天备份** > **端到端加密备份** > **关闭**。

虽然 WhatsApp 已经切换到加密备份，但你的 iPhone 仍然以同样的非加密格式将整个 iPhone 数据备份到 iCloud。出于安全考虑，我们建议您完全禁用 iCloud 备份。为此，打开“**设置**应用程序，从顶部点击您的**个人资料**横幅。然后进入“ **iCloud** ，禁用“ **iCloud 备份**”选项。