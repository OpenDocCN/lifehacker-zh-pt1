# 您需要在切换到新的 Pixel 7 之前完成此操作

> 原文：<https://lifehacker.com/you-need-to-do-this-before-switching-to-your-new-pixel-1849658486>

每当你买了一部新的安卓手机，比如说，[Pixel 7](https://lifehacker.com/is-the-pixel-7-pro-worth-300-more-than-the-pixel-7-1849624470)，你都想让它尽快运行起来。你花在旧手机上的任何时间都是你*可以*花在你花钱买的新手机上的时间。我完全理解这种兴奋，但是请慢一点:在你删除你的旧手机之前，你可能需要采取一个重要的步骤，这个步骤会让你在未来省去很多麻烦。



这个警告是给那些在旧安卓手机上使用谷歌认证器的人的。如果你做了，那对你有好处。该应用程序通过双重认证，是保护你在互联网上众多账户的绝佳方式。多亏了像 Google Authenticator 这样的认证应用，坏演员即使知道你的用户名和密码，也无法侵入你的 Google、Instagram 或 Twitter 账户。最终密钥存在于您的手机中。

但这就是重点:它存在于你的旧手机里。你看，Google Authenticator 不会自动从你的 Pixel 6 跟到你的 Pixel 7。如果你在设置新手机之前删除了旧手机，那些代码就会全部消失。Redditor Kracer20 在过去经历了没有转移他们的谷歌认证应用程序就切换手机的痛苦，这就是为什么他们在 r/GooglePixel 上发布了一个 [有用的 PSA，因为他们知道 subreddit 上的许多人可能会在现在收到他们的新 Pixel 7 或 7 Pro。](https://www.reddit.com/r/GooglePixel/comments/y30p61/it_is_new_phone_day_dont_forget_to_transfer/)

## 如何将谷歌验证码转移到您的新手机上

[谷歌的指令让](https://support.google.com/accounts/answer/1066447?hl=en&co=GENIE.Platform%3DAndroid#zippy=%2Ctransfer-google-authenticator-codes-to-new-phone) 将代码从你的旧谷歌认证器应用转移到你的新应用变得简单。首先，确保你的旧手机上的谷歌认证器是最新的。接下来，在你的新手机上安装 [谷歌认证器](https://play.google.com/store/apps/details?id=com.google.android.apps.authenticator2) ，然后打开应用，选择“开始”在页面底部，选择“重要的现有帐户？”

现在，切换到你的旧手机，打开谷歌认证器，然后点击**更多>转账账户>导出账户**。选取您想要移动到新手机的帐户，然后选取“下一步”这将创建一个二维码。如果您要移动多个帐户，您的手机可能会生成多个代码。在你的新手机上，点击“扫描二维码”，然后扫描你的代码。

一旦你收到应用程序的确认，你的帐户转移，就是这样！在新手机上访问各种 2FA 账户应该没有问题。当然，在抹掉旧手机之前，如果新手机上还没有其他重要数据，如信息、照片、视频和通讯录，请确保它们已经备份并同步。

## 考虑其他认证器选项

正如许多人在 Reddit 帖子中指出的那样，其他认证器应用程序完全避免了这个问题。如果你用 Bitwarden 这样的密码管理器来设置你的 2FA 代码，你可以很容易地在你的新手机上登录你的帐户，并在那里检索你的代码。当然，这有一个安全风险:谷歌认证器只存在于你当前的手机上，而访问你的 Bitwarden 帐户的人也可以获得你的 2FA 代码(在这种情况下，有时被称为 OTP 或一次性密码)。然而，你可能会发现便利大于风险。只要记得让你的 Bitwarden 密码 [强而唯一](https://lifehacker.com/how-to-create-secure-passwords-that-arent-impossible-to-1825048324) 就行了。

另一个不错的选择是 [神盾认证器](https://getaegis.app/) ，一个支持备份的开源认证器 app。这样，如果你的手机报废了，或者你在转移到新手机之前删除了它，你仍然可以无忧无虑地找回你的密码。你也可以考虑 [Authy](https://authy.com/blog/authy-vs-google-authenticator/) ，这是一个跨设备可用的流行替代品，所以你可以在不止是智能手机上访问 2FA。