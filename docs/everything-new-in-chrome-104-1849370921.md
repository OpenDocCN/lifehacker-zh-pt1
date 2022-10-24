# Chrome 104的所有新功能

> 原文:[https://life hacker . com/everything-new-in-chrome-104-1849370921](https://lifehacker.com/everything-new-in-chrome-104-1849370921)

谷歌最新更新，Chrome 104来了。假设你有 [惊人慷慨的系统需求](https://support.google.com/chrome/a/answer/7100626?hl=en) ，你今天就可以更新你的浏览器来利用它的新特性和变化。最大的UI变化是针对运行Chrome OS的Chromebook用户，但所有Chrome用户都将受益于安全补丁。

Watch

## 新的Chrome更新带有27个安全补丁

更新谷歌Chrome最重要的原因是安装它自带的27个安全补丁。需要说明的是，安全形势并不可怕: [根据谷歌Chrome发布博客](https://chromereleases.googleblog.com/) ，Chrome 104修补的27个漏洞中没有一个是“零日”，这意味着没有证据表明这些漏洞已经被恶意用户利用。如果你现在运行的是Chrome 103，你不太可能被这些安全漏洞攻击。也就是说，这27个漏洞现在已经为公众所知，坏人发现如何利用它们来对付没有Chrome 104的用户只是时间问题。

此外，其中七个缺陷被评为“高”，这意味着它们比其他缺陷更具威胁性。以下是完整的列表，顶部列出了“高”级漏洞:

*   [$ 15000][[1325699](https://crbug.com/1325699)]**高**CVE-2022-2603:Omnibox免费后使用。2022-05-16匿名举报
*   [$ 10000][[1335316](https://crbug.com/1335316)]**高** CVE-2022-2604:在安全浏览中免费后使用。由王楠(@eternalsakura13)和360 Alpha Lab的光公于2022-06-10报道
*   [$ 7000][[1338470](https://crbug.com/1338470)]**高** CVE-2022-2605:破晓读出界。由Looben Yang于2022年6月22日报道
*   [$ 5000][[1330489](https://crbug.com/1330489)]**高** CVE-2022-2606:在被管理设备API中免费后使用。由王楠(@eternalsakura13)和360 Alpha Lab的光公于2022-05-31报道
*   [$ 3000][[1286203](https://crbug.com/1286203)]**高** CVE-2022-2607:在标签条免费后使用。由@ginggilBesel于2022-01-11报道
*   [$ 3000][[1330775](https://crbug.com/1330775)]**高** CVE-2022-2608:概览模式下免费后使用。哈利勒·扎尼于2022年6月1日报道
*   [$ TBD][[1338560](https://crbug.com/1338560)]**高** CVE-2022-2609:免费在附近合租后使用。2022-06-22由koocola(@alo_cook)和360漏洞研究院的广工报道
*   [$ 8000][[1278255](https://crbug.com/1278255)]中型CVE-2022-2610:后台获取中的策略执行不足。莫里斯·道尔于2021年12月9日报道
*   [$ 5000][[1320538](https://crbug.com/1320538)]中CVE-2022-2611:全屏API实现不当。由Irvan Kurniawan (sourc7)于2022年4月28日报道
*   [$ 5000][[1321350](https://crbug.com/1321350)]中CVE-2022-2612:键盘输入中旁道信息泄露。由埃里克·克拉夫特(erik.kraft5@gmx.at)和马丁·施瓦兹尔(martin.schwarzl@iaik.tugraz.at)于2022-04-30报道
*   [$ 5000][[1325256](https://crbug.com/1325256)]中CVE-2022-2613:输入免费后使用。Piotr two ek(Vewd)于2022年5月13日报道
*   [$ 5000][[1341907](https://crbug.com/1341907)]中CVE-2022-2614:签到流程免费后使用。由昆仑实验室的raven于2022年7月5日报道
*   [$ 4000][[1268580](https://crbug.com/1268580)]中CVE-2022-2615:cookie中策略执行不足。莫里斯·道尔于2021年11月10日报道
*   [$ 3000][[1302159](https://crbug.com/1302159)]中型CVE-2022-2616:扩展API中不适当的实现。由Alesandro Ortiz于2022年3月2日报道
*   [$ 2000][[1292451](https://crbug.com/1292451)]中CVE-2022-2617:在扩展API中免费后使用。由@ginggilBesel于2022-01-31报道
*   [$ 2000][[1308422](https://crbug.com/1308422)]中CVE-2022-2618:内部不可信输入验证不充分。asnine于2022年3月21日报道
*   [$ 2000][[1332881](https://crbug.com/1332881)]中CVE-2022-2619:设置中不可信输入验证不充分。奥利弗·邓克于2022年6月4日报道
*   [$ 2000][[1337304](https://crbug.com/1337304)]中CVE-2022-2620:在WebUI中免费后使用。由王楠(@eternalsakura13)和360 Alpha Lab的光公于2022-06-17报道
*   [$ 1000][[1323449](https://crbug.com/1323449)]中CVE-2022-2621:在扩展中免费后使用。由Viettel网络安全公司的Huyna于2022年5月7日报道
*   [$ 1000][[1332392](https://crbug.com/1332392)]中CVE-2022-2622:安全浏览中不可信输入验证不充分。由Imre Rad (@ImreRad)和@j00sean于2022-06-03报道
*   [$ 1000][[1337798](https://crbug.com/1337798)]中CVE-2022-2623:离线免费后使用。昆仑实验室的渡鸦于2022年6月20日报道
*   [$ TBD][[1339745](https://crbug.com/1339745)]中CVE-2022-2624:PDF中堆缓冲区溢出。由陈玉昌和张志彦报道，2022-06-27

然而，这并不完全是关于安全更新，根据How-To Geek 的说法 [。下面是升级到Chrome 104时你还能期待的东西(如果你有Chromebook，还有加分)。](https://www.howtogeek.com/822483/whats-new-in-chrome-104/)

## Chrome OS官方支持明暗模式

黑暗模式是任何软件最需要的功能，现在Chrome操作系统中也有了。在最新的更新中，谷歌不仅正式支持亮暗模式之间的切换，而且现在还可以让你自动在它们之间切换。我在我的设备上使用这个功能，所以当太阳开始落山时，一切都进入黑暗模式。

## Chrome操作系统的新开始菜单

另一个很棒的功能:Chromebooks现在有一个类似Windows的开始菜单，被称为“生产力启动器”它配有一个谷歌搜索栏和一个助手快捷方式。另外，在系统托盘的另一侧，你会发现有一个新功能的日期:当你点击它，你会看到一个大的，有用的日历部件。

## 在视频录制中仅共享屏幕的选定部分

任何经常分享他们屏幕的人都会喜欢这一更新: Web应用程序开发人员可以实现一个名为的功能，它允许用户现在裁剪你显示器的一个区域来记录或分享，而不是专注于整个窗口或整个屏幕。此功能有助于缓解过度共享的担忧，让您可以准确控制他人可以看到的屏幕部分。

当然，将由开发者在他们的服务中实现区域捕捉，所以你可能不会马上看到这个特性。It’s由Chrome 104通过驱动。

## LazyEmbeds(有限测试)

谷歌还在测试一项名为LazyEmbeds的功能，该功能仅在网站的嵌入式内容在你的屏幕上可见时才会加载。这是“惰性加载”的副产品，在这种情况下，浏览器只在用户可以看到的时候加载网站内容，而不是一次加载整个网站及其内容。目前，只有1%的Chrome用户会参与这次测试，所以这并不是104版本的全面推广。

## 新开发人员更新

随着Chrome的每一个新版本，谷歌都会为开发者推出新功能。你可以在 [谷歌的DevTools博客](https://developer.chrome.com/blog/new-in-devtools-104/) 和 [Chromium博客](https://blog.chromium.org/2022/06/chrome-104-beta-new-media-query-syntax.html) 以及 [这个DevTools 104视频](https://www.youtube.com/watch?v=4RXWfw7Xg_Y) 上找到完整的变化列表:

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-4RXWfw7Xg_Y&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-4RXWfw7Xg_Y&start=0)

<figcaption class="sc-1ptbguh-0 hxeMec caption">Chrome 104 - What’s New in DevTools</figcaption> 

## 如何更新谷歌 Chrome

幸运的是，在你的电脑上更新Chrome很容易:点击窗口右上角的三个点，然后选择**帮助>关于谷歌Chrome** 。让Chrome加载一会儿——当更新准备好了，你可以点击“重新启动”，这将重启你的Chrome 104浏览器。