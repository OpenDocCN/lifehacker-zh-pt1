# 不要在任何重要的事情上使用应用内浏览器

> 原文：<https://lifehacker.com/dont-use-in-app-browsers-for-anything-important-1849401900>

苹果和谷歌都在防止多站点跟踪方面做了大量工作。谷歌 Chrome 正在慢慢淘汰 cookie，苹果走得最远，要求用户使用他们的 [应用透明](https://support.apple.com/en-us/HT212025) 弹出窗口阻止多应用/多站点跟踪。

Watch

定制的应用内浏览器是他们力所不及的，尽管。默认情况下，这种浏览器很烦人，因为它们没有默认浏览器的历史记录、用户名、密码或共享选项。虽然它们在脸书和 Instagram 等应用中最常见，但它们并不局限于两大元应用。

因为应用程序开发人员自己编写应用程序内的浏览器，所以他们有更多的自由来处理浏览器中发生的事情。浪子开发商 [Felix Krause](https://krausefx.com/blog/ios-privacy-instagram-and-facebook-can-track-anything-you-do-on-any-website-in-their-in-app-browser) 最近的一项研究显示脸书和 Instagram 基本上可以在你使用他们的应用内浏览器时跟踪他们想要的任何东西，默认情况下他们用这个浏览器打开所有的广告和链接。

## 应用内眉毛 er 追踪如何工作？

JavaScript 注入。该研究以 Instagram 为例。Instagram 将 Meta 的 Meta Pixel JavaScript 追踪代码注入你打开的每一个网站。这是一个为网站开发者设计的库，用来跟踪他们网站上的访问者。Meta 在每个网站上注入它，而没有询问网站，并为他们自己收集数据。

当你在 Instagram 中打开一个链接时，应用程序会注入 JavaScript 代码(Meta Pixel)，帮助应用程序查看和记录各种东西。它们可以记录你点击了什么，你打开了什么图像，你在一个页面上花了多长时间，等等。然后，Instagram 会利用这些信息为你提供更多的广告，并为你的身份建立一个更加清晰的图像。

从技术上来说，当你在文本栏中输入密码和信用卡信息时，应用内浏览器甚至可以记录这些个人信息，但是这项研究并没有表明 T2 Meta 正在做任何 T4 邪恶的事情。我重要的是要注意，一个自带内置网络浏览器的随机应用确实有这个能力。

## 关于应用内浏览器追踪，你能做些什么？

首先，无论何时你打开 Instagram、脸书或任何其他带有应用内浏览器的应用的链接，赶紧离开那里。应用程序已经记录了你打开的链接，你对此无能为力，但是你可以停止追踪。Instagram 有一个在默认浏览器中打开网站的选项，隐藏在菜单按钮后面。

另一个选择是停止使用应用程序本身。换成 web app 版本就不用处理这个问题了。如果我们谈论的是 Instagram ，你实际上会得到更好、更平静、无卷轴的体验。

这就是你所能做的一切。对于网站开发人员，Felix 建议了一串代码，这些代码会欺骗 Instagram，使其认为他们的代码已经安装在网站上。他还就苹果如何防止未来出现这种滥用行为提出了建议。如果你想知道他是如何想出这一切的(这是一本很好的读物)，看看这里: [菲利克斯·克劳斯](https://krausefx.com/blog/ios-privacy-instagram-and-facebook-can-track-anything-you-do-on-any-website-in-their-in-app-browser) / [9to5Mac](https://9to5mac.com/2022/08/11/in-app-browsers/#more-826916) 。