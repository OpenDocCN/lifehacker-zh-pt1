# 如何将谷歌助手侵入你的电脑

> 原文：<https://lifehacker.com/how-to-get-google-assistant-on-your-pc-1846417355>

有一天，无论我们喜欢什么平台，每一个数字助理都将触手可及——所以对 Siri、谷歌助理、Alexa 或其他任何人大喊大叫将像点击图标和 [摸索口头命令](https://lifehacker.com/how-to-get-an-amazon-echo-to-tell-you-a-rooms-temperatu-1846399889) 一样容易。然而，在那之前，有一些聪明的变通办法可以让我们的 Windows 或 Mac 桌面上有谷歌助手这样的东西。



如果你想尝试这个魔法，要知道这个实现——由“ [谷歌助手非官方桌面客户端](https://github.com/Melvin-Abraham/Google-Assistant-Unofficial-Desktop-Client) ”提供——并不完美。你将无法从你的桌面访问谷歌程序，也无法访问你最喜欢的流媒体服务。目前还不清楚这是否仅仅是因为这种用途太新，还是因为这是一个难以克服的技术挑战。请继续关注前方。

此外，你必须经历在谷歌云中设置谷歌助手 API 的半费力的过程。这里有一个很好的向导， [会带你经历整个过程](https://github.com/Melvin-Abraham/Google-Assistant-Unofficial-Desktop-Client/wiki/Setup-Authentication-for-Google-Assistant-Unofficial-Desktop-Client) ，所以你会全程得到帮助。然而，这并不是简单的“安装一个应用程序然后*噗！”*一种解决方案。要想在你的桌面上安装谷歌助手，你需要做一些努力。

当我检查这一点时，安装应用程序部分是小菜一碟。启动非官方助手后，当您按照提示进行操作时，您会收到这条不容错过的消息:

从那里，我启动了 [设置指南](https://github.com/Melvin-Abraham/Google-Assistant-Unofficial-Desktop-Client/wiki/Setup-Authentication-for-Google-Assistant-Unofficial-Desktop-Client) ，开始一步步地完成 API 过程。这些说明写得非常好，以至于我用了不到 10 分钟就用谷歌助手 API 启动并运行了这个应用程序——具体来说是 8 分钟，如果你好奇的话。不久之后，我的桌面上有了一个(几乎完全)可用的谷歌助手版本，默认情况下，点击 Windows 的**键+ Shift +一个**热键即可启动。

有趣的是，这是它的基本形式，我建议在你准备好之前，在非官方桌面客户端的主设置窗口中调整几个选项。具体来说:

*   **在应用程序启动时启用麦克风:**如果你的系统上连接了麦克风或网络摄像头，那么这可以确保谷歌助手在你启动应用程序时正在监听。
*   **窗口浮动行为:**选择“模糊时关闭”，当你点击退出时，你的小助手屏幕就会消失。比每次都要点“X”要方便一点。
*   **主题:**选择“使用系统偏好设置”,以便助手窗口与您电脑的主题相匹配，无论您是在明亮、黑暗环境下运行，还是在两者之间频繁切换。

不幸的是，你还不能改变默认热键，以防 Windows **键+ Shift + A** 感觉很麻烦。你可以随时使用*的另一个*应用程序将其重新映射到其他东西上，比如游戏鼠标上的一个按钮或者键盘上的其他东西；但是一旦你习惯了，就没问题了，而且为你的桌面上的虚拟助手付出的代价很小。