# 如何打开环的新的端到端加密

> 原文:[https://life hacker . com/how-to-turn-on-ring-new-end-to-end-encryption-1846060719](https://lifehacker.com/how-to-turn-on-rings-new-end-to-end-encryption-1846060719)

Ring just [为其选定数量的智能家居摄像头添加了端到端加密](https://blog.ring.com/2021/01/13/ring-launches-video-end-to-end-encryption/) n (E2EE)，为您的戒指设备录制的视频提供了额外的安全保护。这仍然不能让我们对铃声设备感到兴奋，确切地说，考虑到所有 [问题](https://techcrunch.com/2021/01/14/ring-neighbors-exposed-locations-addresses/)[平台](https://lifehacker.com/how-to-prevent-ring-from-sharing-your-data-with-marketi-1841768023) [有](https://lifehacker.com/how-to-kick-hackers-out-of-your-ring-account-1840507643) [经历过](https://lifehacker.com/if-you-use-amazons-ring-doorbell-devices-change-your-w-1839721221) ，但是如果你已经在使用门铃的话，这个功能值得了解一下

Watch

Ring的视频在上传到Ring的云服务器时是加密的，但这一新功能通过额外的AES 128位加密层保护它们,只能在Ring的E2EE计划中注册的移动设备上解密和观看。(你可以在 [最近发布的白皮书](https://assets.ctfassets.net/a3peezndovsu/5jmqFoKyaCXpL2qBG46Zqn/72d138d896e7460c5bdae07992ad491e/Ring_Encryption_Whitepaper.pdf) 中了解更多关于Ring的E2EE政策。)

E2EE可以阻止外人截取和观看正在录制或发送到您的设备上的视频；甚至连戒指都无法解密它们。然而，Ring的E2EE也禁用了用户端的一些功能，包括动作验证和在亚马逊Echo Show或Fire TV设备上观看Ring camera直播的能力。你录制的视频会更安全，但你会失去实时观看和基于云的监控功能，这些功能可能与E2EE增加的额外加密层一样重要。

如果你对这些权衡不感冒，打开Ring的新E2EE很容易——只要你有合适的硬件。E2EE在发布时仅在少数设备上提供:

*   视频门铃专业版
*   精英视频门铃
*   泛光灯凸轮
*   室内摄像机
*   有线聚光灯摄像头
*   聚光灯凸轮支架
*   向上插入凸轮插头
*   竖起凸轮精英

将来可能会增加进一步的支持，但现在，你需要这些设备中的一个来使用E2EE。你还需要在你想要注册的任何安卓[iOS设备](https://apps.apple.com/us/app/ring-always-home/id926252661) 上安装最新版本的Ring应用程序。如果您符合这些要求，您可以在Ring应用程序中打开E2EE:

1.  打开戒指app。
2.  进入**控制中心>视频加密>高级设置。**
3.  选择**“视频端到端加密”**
4.  轻按滑块打开该功能，然后轻按**“开始”**
5.  按照应用内说明将您的帐户、移动设备和环形摄像机注册到端到端加密中。
6.  您可以通过关闭**“视频端到端加密”**滑块随时禁用E2EE。

安装过程中会要求您生成密码，不要忘记！它无法恢复，您拥有的任何加密视频都将丢失。你必须使用另一个移动设备重新开始才能再次使用E2EE。