# 现在如何试用即将到来的火狐改版

> 原文：<https://lifehacker.com/how-to-try-out-the-upcoming-firefox-redesign-now-1846221037>

今年晚些时候，Mozilla 将使用新的质子界面更新 Firefox 的桌面设计。目视检查预计包括:

*   精简的“汉堡”菜单: Mozilla 将移除图标，使菜单完全基于文本。几个选项也将被重命名、合并或完全删除。
*   **个性化的新标签页:**您可以更改新标签页的外观和布局，包括出现的链接、推荐和新片段的数量。
*   信息栏和通知变化: Firefox 的通知将会有更多的颜色，使消息更有个性。

Watch

这些是我们根据 [早期外观和](https://techdows.com/2021/01/an-early-look-at-firefox-proton-user-interface.html) 泄露了解到的主要变化；火狐 89 的质子设计的最终版本可能包括更多的调整和更新。重新设计将于 5 月份推出，但你可以通过安装 Firefox Beta、Nightly、或 Dev build 和在浏览器的实验设置中打开新的界面变化来获得早期的外观。

### 在 Firefox Beta、Nightly 或 Dev 版本的早期打开质子界面

1.  下载并打开 [Firefox Beta，Nightly，或者 Dev](https://www.mozilla.org/en-US/firefox/channel/desktop/) 。
2.  在一个新标签页中转到**关于:配置**。
3.  点击**“接受风险并继续。”**
4.  搜索" **browser.proton.enable"**
5.  单击箭头图标打开设置。
6.  重启 Firefox 以应用更改。

启用 browser.proton 设置后，使用相同的方法打开它们:

*   新质子标签:**browser . proton . tabs . enabled**
*   新汉堡菜单:**browser . proton . appmenu . enabled**
*   新建新建标签页:**browser . newtabpage . activity-stream . newtaexperience . enabled**

如果要求您添加这些设置，请选择**“布尔”，**，然后单击**“+”**添加设置，然后单击箭头启用并重启浏览器。

重启 Firefox 后，任何可用的质子界面元素都会出现。一些用户可能不会马上看到每一个新界面的变化，所以在接下来的几周继续查看 Mozilla 是否会推出新的东西给你。

### 在稳定版早期启用火狐的质子界面

虽然预发布的 Firefox 版本有最多的预启用选项，但稳定版本也可以让您预览质子界面:

1.  打开 Firefox，进入**关于:配置**
2.  点击**“接受风险并继续。”**
3.  使用搜索栏查找 browser.proton.enable
4.  点按箭头图标将设置变为“真”
5.  重启 Firefox

稳定版不会马上出现新东西；更改必须在服务器端启用。这样，当任何早期更新正式发布时，你就会收到它们。