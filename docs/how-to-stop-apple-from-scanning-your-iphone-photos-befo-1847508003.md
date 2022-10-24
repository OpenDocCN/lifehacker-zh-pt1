# 如何在iOS 15到来之前阻止苹果扫描你的iPhone照片

> 原文:[https://life hacker . com/how-to-stop-apple-from-scanning-your-iphone-photos-befo-1847508003](https://lifehacker.com/how-to-stop-apple-from-scanning-your-iphone-photos-befo-1847508003)

从iOS 15和iPadOS 15开始，苹果将在扫描你上传到iCloud的照片时应用新的儿童保护政策。这项政策将有助于苹果向当局报告非法儿童色情图像，从表面上看，这听起来像是苹果正在做的一件好事。但是围绕他们是如何做到的有很多争议和困惑，所以让我们来谈谈它是如何工作的，然后如果你想阻止苹果扫描你的iPhone照片，你可以做些什么。

Watch

## 苹果的iPhone照片扫描功能是如何工作的

困惑的部分原因在于，苹果同时宣布了两项儿童安全功能，但它们的工作方式完全不同。

首先是针对iCloud照片的 [儿童色情扫描功能](https://www.apple.com/child-safety/pdf/Expanded_Protections_for_Children_Frequently_Asked_Questions.pdf) 。在这里，苹果扫描儿童色情照片的数字指纹，并将其与CSAM(儿童性虐待材料)数据库中的非法图像进行匹配。CSAM由失踪和被剥削儿童中心维护，这是美国的一个准政府机构

第二个功能是基于机器学习的选择性加入功能，仅限于iPhone和iPad上的Messages应用程序。这用于提醒孩子或他们的父母注意“信息”应用程序中的色情图像。

争议围绕着第一个，iCloud Photos扫描功能，该功能默认为所有iCloud Photos用户启用。当你的iPhone将照片上传到iCloud Photos(如果你启用了iCloud Photos功能)时，会有一个多部分算法在你的设备上对照片进行一些分析，然后将其发送到iCloud。然后，iCloud做另一部分的分析；如果你达到30张已知儿童色情图片的门槛，苹果就会标记你的账户。

然后，苹果的手动审查过程开始，苹果知道被标记的图像(而不是其余的图像)。然后，苹果将照片发送给CSAM项目，当局从那里接管。

苹果公司表示，该程序仅针对CSAM已知的儿童色情数据库运行，并不标记常规色情内容、裸照或例如你孩子在浴缸中的照片。苹果在这里的流程是安全的，克雷格·费德里基在最近的《华尔街日报》采访 中谈到了技术细节。如果你很好奇，可以看看下面的视频。

 [https://lifehacker.com/embed/inset/iframe?id=youtube-video-OQUO1DSwYN0&start=0](https://lifehacker.com/embed/inset/iframe?id=youtube-video-OQUO1DSwYN0&start=0) 

据苹果公司称，这里没有真正的照片扫描。本质上，苹果给你的照片分配一个“神经哈希”(识别你照片的一串数字)，然后将其与CSAM数据库中的哈希进行比较。然后，它将这一过程与图像一起保存在苹果所谓的安全凭证中。

然后，它会根据这些散列进行更多的分析和匹配；如果30个安全凭证具有CSAM图像的匹配，则只有*然后*被系统标记为您的帐户，以便人工审查者进入实际查看是否有非法图像，并且图像和帐户被报告。

## 如何阻止苹果扫描你的iPhone照片

所以，现在你知道了系统是如何工作的，你可以选择是否要阻止苹果这样做。这种扫描仅在照片上传到iCloud时发生。

苹果不会扫描在WhatsApp或Telegram等即时通讯应用中发送的照片。尽管如此，如果你根本不想让苹果进行这种扫描，你唯一的选择就是禁用iCloud Photos。为此，在你的iPhone或iPad上打开“**设置**”应用，进入“**照片**”部分，并禁用“ **iCloud照片**”功能。从弹出菜单中，选择“**下载照片&视频**”选项，从您的iCloud照片库中下载照片。

您还可以使用 [iCloud网站](http://www.icloud.com) 将所有照片下载到您的电脑中。你的iPhone现在将停止向iCloud上传新照片，Apple现在不会扫描你的任何照片。

寻找替代品？真的没有。所有主要的云备份提供商都有相同的扫描功能，只是他们完全在云中进行扫描(而苹果混合使用设备上扫描和云扫描)。如果您不想进行这种照片扫描，请使用本地备份、NAS或完全端到端加密的备份服务。