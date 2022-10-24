# 更改这些子块原点设置以获得更多隐私

> 原文：<https://lifehacker.com/change-these-ublock-origin-settings-for-even-more-priva-1848995058>

uBlock Origin 是最好的保护互联网隐私的浏览器扩展之一。它的默认设置对大多数人来说很棒，但是通过的一些调整，它会更加有效。在做出这些改变之前，请记住你启用的屏蔽选项越多，破坏网页的风险就越高。理想情况下，你应该一次做一个调整，看看你最常用的网站是否仍然像预期的那样运行。



以下是你应该启用的最好的 uBlock Origin 特性，以获得最大的隐私保护。

## 隐藏恼人的 cookie 横幅

许多网站被法律强制要求告诉你他们使用 cookie，并允许你拒绝不必要的 cookie。你可以使用 [一个单独的扩展来自动拒绝这些 cookie 通知](https://lifehacker.com/you-can-block-those-annoying-cookie-banners-on-every-we-1848936142) 或者使用 uBlock Origin 来隐藏它们。

单击浏览器工具栏中的 uBlock 原点图标，然后选择三个齿轮图标。这将打开 uBlock Origin 的仪表板。要隐藏 cookie 通知，进入**过滤列表**，在**烦恼**下，启用 **EasyList Cookie** 。

## 启用特定于区域的阻止列表

只要你访问国际网站，uBlock Origin 的默认黑名单将为你服务。然而，如果你经常访问地区网站，追踪器仍然可能会错过这些街区。这就是为什么您应该考虑使用特定于地区的阻止列表。进入 **uBlock Origin dashboard >过滤列表>地区、语言**，选择您所在地区的阻止列表。

## 阻止已知包含恶意软件的域

大量的网站存在传播病毒和恶意软件，uBlock Origin 可以阻止其中的大部分。您可以通过转到 **uBlock Origin dashboard >过滤器列表>恶意软件域、**来启用这些过滤器，并启用**在线恶意 URL 阻止列表**、**网络钓鱼 URL 阻止列表**(阻止骗子使用的域)和 **PUP Domains 阻止列表** (p 潜在有害程序)。

## 从 URL 中删除跟踪

如果你在几乎任何网站上点击一个 URL，你会在浏览器的地址栏中看到一长串令人讨厌的字符。这是因为网站使用 URL 来跟踪您的活动。uBlock Origin 有多种方法可以从 URL 中删除跟踪信息，你可以使用其中的任何一种。

阻止跟踪 URL 的最简单方法是进入**uBlock Origin dashboard>过滤列表>隐私**并启用 **AdGuard URL 跟踪保护**。

如果你习惯于修改阻止列表和你自己的阻止规则，进入 **uBlock Origin dashboard >过滤器列表>我的过滤器**和添加这行代码:

`*$removeparam=/^utm_/`

这将从 URL 中删除使用 utm 参数的跟踪信息。您可以查看 uBlock Origin 的文档，了解[**remove param**](https://github.com/gorhill/uBlock/wiki/Static-filter-syntax#removeparam)语法，以便更好地理解它并创建有效的过滤器。

您也可以导入一个自定义列表来删除对 URL 的跟踪。为此，进入**子块原点仪表板>过滤列表>自定义**，并选择**导入**。P 在导入按钮下面的表单中粘贴以下 URL:

[`https://raw.githubusercontent.com/DandelionSprout/adfilt/master/LegitimateURLShortener.txt`](https://raw.githubusercontent.com/DandelionSprout/adfilt/master/LegitimateURLShortener.txt)T4】

## 停止远程字体和 JavaScript

uBlock Origin 允许您阻止 JavaScript 和加载远程字体。这可以让你更快地加载一些网站，越过某些付费墙，并减少跟踪。然而，它也可以破坏很多网站，因为几乎每个现代网站都使用 JavaScript，所以在启用它之前要小心。

进入到**子块原点仪表盘>设置>默认行为**，启用 **块远程字体**和**禁用 JavaScript** 。

## 探索高级阻止模式

对于更高级的用户，uBlock Origin 在[【GitHub】](https://github.com/gorhill/uBlock/wiki/Blocking-mode)上记录了它的高级阻止模式，如果你想试试的话。收益递减法则在这里适用，不过:你应该意识到，为了移除几个额外的追踪器，你会大大增加破坏网站的风险，这对大多数人来说是不值得的。