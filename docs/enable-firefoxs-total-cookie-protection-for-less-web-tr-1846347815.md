# 启用 Firefox 的“全面 Cookie 保护”,减少网络跟踪

> 原文：<https://lifehacker.com/enable-firefoxs-total-cookie-protection-for-less-web-tr-1846347815>

我们不太可能过上没有追踪器的网上生活，但是我们很感激这些公司尽他们所能，至少在技术上让追踪用户变得更加困难。如果你是火狐的粉丝，Mozilla 刚刚推出了一个新的“全面 Cookie 保护”模式，基本上隔离了一个网站的所有 Cookie。借用 Mozilla 的比喻，每个网站都有自己的“饼干罐”，饼干就在那里；它们不能与任何其他网站共享。



正如 Mozilla [中写的](https://blog.mozilla.org/security/2021/02/23/total-cookie-protection/) :

> 当跨站点 Cookie 需要用于非跟踪目的时，Total Cookie Protection 会对其进行有限的例外处理，例如受欢迎的第三方登录提供商所使用的 Cookie。只有当 Total Cookie Protection 检测到您打算使用某个提供商时，它才会允许该提供商专门为您当前访问的站点使用跨站点 Cookie。这种短暂的异常允许强大的隐私保护，而不影响您的浏览体验。
> 
> *与我们上个月宣布的* [*Supercookie 保护*](https://blog.mozilla.org/security/2021/01/26/supercookie-protections/) *相结合，Total cookie 保护在 Firefox 中的网站之间提供了 Cookie 和其他站点数据的全面分区。这些功能一起防止网站能够“标记”您的浏览器，从而消除了最普遍的跨站点跟踪技术。*

这种方法*应该*允许 Firefox 更有效地阻止基于 cookie 的跟踪，句号，而不是依赖于 Mozilla 无法控制的列表来推动其常规的阻止实现——其增强的跟踪保护。Mozilla 的 Johann Hofmann 和 Tim Huang 写道，问题在于:

> 为了对抗网络追踪，Firefox 目前依靠增强追踪保护(ETP ),根据断开列表阻止已知追踪者的 cookies 和其他共享状态。这种形式的 cookie 拦截是停止跟踪的有效方法，但它有其局限性。ETP 保护用户免受 3000 种最常见和最普遍的已识别跟踪器的攻击，但它的保护依赖于列表是完整的并且总是最新的这一事实。确保完整性是很困难的，追踪者可以通过注册新的域名来规避名单。此外，识别追踪器是一项耗时的任务，并且在将新的追踪域添加到列表之前，通常会增加几个月的延迟。

理论上，Mozilla 在 Firefox 中开辟出的“cookie jar”方法的例外仍然允许用户使用单点登录来登录网站。让我们祈祷公司不会找到一种方法来利用 Mozilla 为第三方 cookies 提供的这些合法用例的灵活性。

和往常一样，最好的方法是使用火狐的保护作为*你广告战武库中的一个*工具，但不是唯一的。首先，您需要启用 Firefox 增强跟踪保护的严格版本，以利用新的“cookie jar”方法。标准模式不能满足要求:

从那里，安装一些你最喜欢的限制跟踪和广告的扩展，你应该设置好了。我们最喜欢的包括:

*   [**uBlock 原点**](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) (或者更好玩的工具比如)
*   [**隐私獾**](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)T5】
*   [](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=recommended)
*   **[**乌马特里克斯**](https://addons.mozilla.org/en-US/firefox/addon/umatrix/)T5】**
*   **[](https://addons.mozilla.org/en-US/firefox/addon/noscript/)**
*   ****[**多账户容器**](https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/)****
*   ****[](https://addons.mozilla.org/en-US/firefox/addon/clearurls/)****