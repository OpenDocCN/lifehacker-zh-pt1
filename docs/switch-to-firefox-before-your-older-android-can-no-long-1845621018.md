# 在你的旧 Android 不能访问部分网页之前，切换到 Firefox

> 原文：<https://lifehacker.com/switch-to-firefox-before-your-older-android-can-no-long-1845621018>

我知道这种想法很奇怪，但这是真的:从明年 9 月开始，Android 7.1 或更早版本的用户——这大约是目前使用 Android 的三分之一——可能无法连接到任何使用 SSL 证书的网站。为了保持一致，这大概是万维网的 [三分之一](https://www.androidpolice.com/2020/11/07/many-websites-will-stop-working-on-older-android-versions-in-2021/) 。

Watch

至于为什么，简而言之就简单了。大约 95%的网络 [使用如今的 HTTPS](https://transparencyreport.google.com/https/overview?hl=en)——这是一个很好的浏览器安全指标。然而，启动一个新的认证中心的过程有点痛苦，这个认证中心负责发布数字证书，网站使用 [作为【HTTPS】](https://howhttps.works/)的一部分。正如雅各布·霍夫曼-安德鲁斯在《让我们加密:

> 当一个新的证书颁发机构(CA)出现时，它面临一个难题:为了对人们有用，它需要它的根证书被各种各样的操作系统(OS)和浏览器信任。然而，操作系统和浏览器可能需要数年时间来接受新的根证书，人们甚至需要更长时间来将他们的设备升级到包含这一变化的新版本。常见的解决方案是:一个新的 CA 通常会向一个现有的可信 CA 请求交叉签名，以快速获得许多设备的信任。
> 
> 五年前，当 Let's Encrypt 推出时，我们正是这么做的。我们从 IdenTrust 得到了一个交叉签名。他们的“DST 根 X3”已经存在了很长时间，所有主要的软件平台都已经信任它:Windows、Firefox、macOS、Android、iOS 和各种 Linux 发行版。这种交叉签名允许我们立即开始签发证书，并让它们对许多人有用。没有 IdenTrust,“让我们加密”可能永远不会发生，我们非常感谢他们的合作..."

正如你可能已经猜到的，这个最初的 DST 根 X3 证书将于明年到期——具体来说是 9 月 1 日——任何没有更新到使用 Let's Encrypt 的 ISRG 根 X1 证书的操作系统都将遇到问题。虽然你可能会很快遇到问题，因为 Let's Encrypt 将在 1 月份修改其自动认证流程，改为为网站 ISRG 根 X1 证书提供服务。他们将能够建立一个与 DST 根 X3 证书向后兼容的解决方案，但这只是一个临时的解决方案。

### 对于这些不兼容的 SSL 证书，您能做些什么？

在一个完美的世界里，你的旧 Android 会收到一个不支持的更新，允许它使用 Let's Encrypt 的新证书。我不会对此抱太大希望，因为制造商可能会非常厌恶更新那些可能永远也不会升级到 Android 8 的“古老”Android 设备。

你确实有一个小小的变通办法:如果你从你目前使用的任何浏览器切换到 [Firefox Mobile](https://play.google.com/store/apps/details?id=org.mozilla.firefox) ，你就可以访问任何你想访问的网站。Firefox Mobile 使用自己的根证书，而不是你的 Android 操作系统支持的任何东西，所以如果你的 Android 制造商拒绝发布更新，你可以毫无问题地查看任何你想要的网站。

d 暂时不要删除 Chrome。G oogle 将， [在某个时候](https://www.zdnet.com/article/chrome-will-soon-have-its-own-dedicated-certificate-root-store) ，切换到使用自己的根证书的类似做法，而不是在 Chrome 的底层操作系统上找到的根证书。目前还不清楚这是否会在未来一两个月内推出，但我假设它肯定会在明年 9 月份准备好，届时旧机器人将正式被淘汰。