# 什么是 EXIF 数据，如何从照片中删除它

> 原文：<https://lifehacker.com/what-is-exif-data-and-how-to-remove-it-from-your-photo-1845292669>

每次使用数码相机或智能手机拍照时，您的设备都会向图像文件添加额外的信息，即存储在图像本身中的有关图像的元数据。众所周知，这种 EXIF 数据是“可交换图像文件格式”的缩写，它包括原始照片的日期、时间和地理位置。



它还可以包括相机设置，如:

*   你的相机型号
*   孔
*   快门速度
*   焦距
*   计量模式
*   ISO 速度
*   图像方向(横向或纵向)
*   您拍摄的图像的缩略图

为什么 EXIF 数据很重要？照片应用程序可以使用它来按照确切的日期、时间和位置整理照片。专业摄影师可以拨回老照片，并使用 EXIF 数据来查看他们使用的精确相机设置。您甚至可以将版权信息添加到照片的 EXIF 数据中。

另一方面，执法机构已经使用 EXIF 的数据来寻找罪犯——这是 2012 年约翰·迈克菲 [的一个臭名昭著的“oopsie”时刻。](https://nakedsecurity.sophos.com/2012/12/03/john-mcafee-location-exif) EXIF 的数据甚至可以用来证明一张照片是在何时何地拍摄的，前提是这张照片没有被篡改过。最近的 [审查川普总统所谓的后 COVID 恢复照片](https://www.cnet.com/news/whats-this-exif-technology-people-used-to-study-trump-photos-faq) 就是一个完美的例子。

### 如何查看照片中的 EXIF 数据

你的照片的元数据总是存在的，但是当你盯着你拍摄的图像看时，它并不立即可见。要查看它，您需要访问文件的属性。对于保存在 Windows 或 Mac 电脑上的文件，或者使用 Google Photos 保存在 iOS 和 Android 上的文件，您可以轻松地做到这一点。

#### **视窗:**

1.  右键单击已保存的图像文件。
2.  选择**属性。**
3.  选择**“详细信息”**选项卡查看图像的元数据。

#### **Mac:**

1.  单击以高亮显示图像文件。
2.  按下**“Command+I”。**
3.  点击信息查看器中的**“Exif”**选项卡。

#### **谷歌照片(Android/iOS):**

1.  在 Google 相册中打开一张图片。
2.  点击**“I”**图标查看 Exif 数据。

#### **浏览器扩展:**

像火狐浏览器[Exif Viewer](https://addons.mozilla.org/en-US/firefox/addon/exif-viewer)和[Chrome 浏览器](https://chrome.google.com/webstore/detail/exif-viewer-classic/nafpfdcmppffipmhcpkbplhkoiekndck) 上的 Exif 浏览器 Classic，或者像[【Verexif.com】](https://www.verexif.com/en)这样的网站可以让你查看网上上传的 JPEGs 格式的 EXIF 数据。

### 如何编辑和删除 EXIF 数据

EXIF 数据可以告诉您很多关于照片的信息，但是您可以轻松移除或修改不想共享的元数据。这保护了你的隐私，但也使 EXIF 数据作为“确凿证据”的实用性降低，除非照片的元数据与其他事实相符这一点相当明显。

像 Adobe 的 Photoshop 或 Lightroom 这样的程序可以让你编辑 EXIF 数据，像 Instagram、Imgur 和 Twitter 这样的社交媒体平台可以在上传之前从图像中删除 EXIF 数据。

您也可以直接从 Windows 桌面执行此操作:

1.  右键单击已保存的图像文件。
2.  选择**属性。**
3.  选择**“详细信息”**选项卡。
4.  点击**“删除属性和个人信息”**
5.  选择是要创建删除所有可能的元数据的备份，还是只删除指定的数据而不制作副本。
6.  单击您想要删除的每条信息，然后单击**“确定”**

Mac 用户将需要一个额外的应用程序来删除 EXIF 数据。如前所述，Photoshop 和 Lightroom 可以提供帮助。也有几个免费的第三方程序可以替代使用，比如 [ImageOptim](https://imageoptim.com/mac) 或者 [EXIF Purge](http://www.exifpurge.com) 。

Android 和 iOS 用户 [可以关闭地理标记](https://lifehacker.com/psa-your-phone-logs-everywhere-you-go-heres-how-to-t-1486085759) 以防止他们的手机将地理位置数据添加到他们的照片中，但当你拍照时，其他 EXIF 数据仍会被记录。有一些应用程序可以帮你删除这些元数据，但是很多要么充斥着广告，要么很贵，要么可能很粗略。最安全的选择是使用上面的桌面应用程序之一来删除照片的 EXIF 数据。