# 该工具检查应用内浏览器是否在跟踪你

> 原文：<https://lifehacker.com/this-tool-checks-if-in-app-browsers-are-tracking-you-1849443044>

[与功能齐全的浏览应用相比，应用内浏览器是垃圾](https://lifehacker.com/dont-use-in-app-browsers-for-anything-important-1849401900) ，但它们也是一个主要的隐私和安全风险。许多应用程序使用一种称为 Javascript 注入的方法，将数据追踪器偷偷放到你通过应用程序内浏览器访问的网站上，这种方法会在页面加载时向页面添加额外的代码。这些追踪器可以收集浏览历史、登录数据，甚至键盘输入和文本输入。

Watch

虽然 Javascript 注入并不总是用于邪恶的手段，但它是一个潜在的安全威胁，直到现在，很难在应用内浏览器中检查它。幸运的是，安全研究人员 Flix Krause 的新应用程序命名工具 [InAppBrowser](https://inappbrowser.com/) ，检查应用程序的内置浏览器是否使用潜在危险的 Javascript 注入来跟踪你的数据。

虽然 InAppBrowser 只适用于内置 web 浏览器工具的应用程序，如抖音、Instagram 或 Messenger，但您也可以在桌面上使用它来检查浏览器扩展中的 Javascript 注入。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-i2SfbHpZDQI&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-i2SfbHpZDQI&start=0)

<figcaption class="sc-1ptbguh-0 hxeMec caption">InAppBrowser.com in Instagram</figcaption> 

如果你对某个应用或浏览器扩展有所怀疑，试试 InAppBrowser，看看它是否有什么可疑之处。方法如下:

1.  **在移动端【iOS/Android】:**打开你想要测试的应用，在应用内置的网页浏览器中加载[【inappbrowser.com】](https://inappbrowser.com/)。一个简单的方法是在邮件、评论或帖子中将链接发送给自己。或者，在应用程序中打开一个网站的链接(任何网络链接都可以)，然后前往[https://inappbrowser.com。](https://inappbrowser.com)T9】
2.  **在桌面:**要在桌面上测试网站和浏览器扩展，请打开您喜欢的浏览器，进入【inappbrowser.com】。
3.  一旦网站加载，你会看到一条消息，详细说明浏览器拦截的任何潜在的粗略 Javascript 行为(如果有的话)，以及代码用途的解释。

这些读数可以帮助您发现可能的恶意行为，但有几个警告需要提及。

最重要的是，InAppBrowser 只是提醒你 Javascript 注入的存在，并不能判断一个应用或浏览器扩展是否实际上是恶意的。它甚至会标记使用 Javascript 注入的应用程序和浏览器扩展，但*根本不会*跟踪你。这意味着阻止网站追踪器的私人浏览扩展、出于广告或故障排除原因收集浏览数据的应用程序(如抖音)，以及直接监视你的恶意应用程序都将发出相同的警告。甚至克劳斯 [也警告说，如果一个应用使用 Javascript 注入，就不要妄下结论](https://krausefx.com/blog/ios-privacy-instagram-and-facebook-can-track-anything-you-do-on-any-website-in-their-in-app-browser) 。

同样，InAppBrowser 无法提醒你其他形式的跟踪应用程序、浏览器和网站可能会使用。这意味着一个应用程序可能会通过 InAppBrowser 的测试，但仍然会通过其他方式收集你的数据，所以不要依赖 InAppBrowser 作为测试应用程序安全性的唯一方法。尽管如此，了解一个应用程序是否使用 Javascript 注入还是很重要的——不管是恶意的还是其他的——这样你就可以自己决定这个应用程序是否值得使用。

如果你发现一个应用程序可能在跟踪你，你想阻止它，你有几个选择。最好的解决办法是删除 app。如果不在你手机上，它就追踪不到你。

如果你想保留一个应用程序，但抑制其跟踪，请前往应用程序的设置，看看你是否可以将默认浏览器更改为你喜欢的应用程序，如 Safari、Firefox 甚至 Chrome。Safari 是一个特别好的选择，因为最近的版本阻止了 AppBrowser 警告的许多 Javascript 行为。

另外，在 iOS 或安卓 [设置菜单](https://lifehacker.com/how-to-preemptively-block-ad-tracking-on-your-android-1847034618) 中 [禁用应用追踪。这对 iOS 用户来说更有效，但它也会妨碍 Android 上的广告跟踪。](https://lifehacker.com/how-to-stop-your-iphone-and-its-apps-from-tracking-your-1847585595) [关闭位置跟踪，以及](https://lifehacker.com/psa-your-phone-logs-everywhere-you-go-heres-how-to-t-1486085759) 。坦率地说，我们建议调整这些设置，即使你使用的每个应用程序都通过了 Javascript 检查测试。

[ [出血电脑](https://www.bleepingcomputer.com/news/security/new-tool-checks-if-a-mobile-apps-browser-is-a-privacy-risk/)