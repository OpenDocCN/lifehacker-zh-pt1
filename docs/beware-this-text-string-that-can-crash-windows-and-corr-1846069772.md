# 小心这个文本字符串，它会使Windows崩溃并“损坏”你的硬盘

> 原文:[https://life hacker . com/当心-this-text-string-than-can-crash-windows-and-corr-1846069772](https://lifehacker.com/beware-this-text-string-that-can-crash-windows-and-corr-1846069772)

黑客正在利用一个奇怪的漏洞，如果你提取一个ZIP文件， 打开一个特定的文件夹，甚至点击一个Windows快捷方式，一个简单的文本字符串就会“破坏”你的Windows 10或Windows XP电脑的硬盘。黑客将文本字符串添加到一个文件夹的位置，当你打开它的时候，砰— 硬盘出现问题。

Watch

或者当你在Windows 10中看到“重启以修复硬盘错误”警告时，你可能会假设。您的数据很有可能是正确的，但是您仍然需要运行 chkdsk来确认。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1349836787837923329&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1349836787837923329&autosize=1) 

该漏洞首先由安全研究员 [乔纳斯L](https://twitter.com/jonasLyk/status/1347900440000811010) 发现并披露，随后 [将CERT协调中心的门卫](https://twitter.com/wdormann/status/1347958161609809921) 证实了那些 e的发现。根据Doorman的说法，这个缺陷是Windows 10中多年来一直没有解决的许多类似问题之一。更糟糕的是，除了打开一个文件夹，还有更多方式来执行攻击。

 [https://lifehacker.com/embed/inset/iframe?id=twitter-1349983599865466881&autosize=1](https://lifehacker.com/embed/inset/iframe?id=twitter-1349983599865466881&autosize=1) 

根据哔哔声计算机 对 [的测试，即使快捷图标*简单地指向*一个有讹误文本的位置，该文本串似乎也是有效的。你也不必点击或打开文件；只要让它出现在你的桌面上就足以执行攻击。文本字符串也适用于ZIP文件、HTML文件和URL。](https://www.bleepingcomputer.com/news/security/windows-10-bug-corrupts-your-hard-drive-on-seeing-this-files-icon/)

微软正在调查这个问题，但不知道是否或何时会出现修复程序。正如一位公司发言人告诉的:

“我们知道这个问题，并将在未来的版本中提供更新。这项技术的使用依赖于社会工程，我们一如既往地鼓励我们的客户在网上实践良好的计算习惯，包括在打开未知文件或接受文件传输时保持谨慎。”

在此期间，不要点击可疑链接或打开未知文件。也就是说，这是一个不寻常的错误，可以通过多种方式被利用，文本字符串可能会在意想不到的地方弹出。

然而，如果病毒破坏了你的硬盘，你还没有完全完蛋。您可能必须运行自动或手动驱动器扫描和修复，但这整个过程可能会对您的电脑造成比预期更大的破坏。我们的建议？保留你的文件 [备份](https://lifehacker.com/our-favorite-ways-to-back-up-a-windows-pc-1845994254) ，以防你遇到的怪异情况像这样——或者任何意外的数据丢失。你怎么小心都不为过。那样的话，如果你绝对*有*到T11】从零开始重装WindowsT13】就不会是灾难，只是麻烦事。