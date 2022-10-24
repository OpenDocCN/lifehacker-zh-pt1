# 你也应该使用 GeForce Experience 来优化你的应用程序

> 原文：<https://lifehacker.com/you-should-use-geforce-experience-to-optimize-your-apps-1846700196>

Nvidia 的 GeForce 体验软件的新版本现已推出。此次更新包含了新功能、扩展的设备和游戏支持以及错误修复，但有两个新功能将有助于所有那些你不在电脑上玩游戏的时刻: [自动应用优化](#apps) 和[OBS 降噪](#noise) 。

Watch

### 创意应用的优化性能设置

GeForce Experience 现在可以优化 Adobe Lightroom、Adobe Substance Designer、AutoCad、DaVinci Resolve 等创意软件的设置。每当发布新的更新时，该应用程序还会下载最新的 Nvidia Studio 驱动程序。

GeForce experience 支持的软件列在 GeForce Experience 应用程序的“游戏和应用程序”部分。使用 Nvidia 最佳设置的应用程序将显示绿色勾号。如果您需要快速查看哪些应用程序可以从 Nvidia 构建的调整中受益，请寻找灰色圆圈。

您不必强制使用 Nvidia 的最佳设置，但它们在某些情况下可以提高性能，可能值得一试。方法如下:

1.  在 GeForce Experience 中，选择**“游戏和应用”**选项卡。
2.  将鼠标放在应用程序的缩略图上将其高亮显示，然后点击**“详细信息”**
3.  在详细信息页面，点击设置部分上方的**“优化”**。

这将应用 Nvidia 根据您的电脑硬件推荐的设置，但您也可以调整这些设置以提高性能或视觉质量(或者完全关闭它们):

1.  在应用程序的详细信息页面中，单击设置部分上方的扳手图标。
2.  向“质量”或“性能”方向调整滑块
3.  点击**“应用”**保存您的更改。该应用程序会相应地调整您的设置。
4.  如果您根本不想使用 Nvidia 的最佳设置建议，请单击**“Revert”**撤销更改。您可能还需要在应用程序中调整设置。

### 对 OBS 的 Nvidia 噪声消除支持

GeForce Experience 还增加了对 [OBS](https://lifehacker.com/how-to-stream-or-record-your-games-for-broadcast-online-1702860349) 的原生 Nvidia 降噪支持，这是最受欢迎的直播流媒体工作室应用之一。Nvidia 的噪音消除技术使用 RTX 2000 或 3000 系列 GPU 中的 AI 核心来消除扬声器、PC 风扇或其他环境声音的背景噪音，而不会影响您的声音。

这对于那些喜欢使用扬声器而不是耳机、喜欢用噼啪作响的街机格斗棍玩格斗游戏或喜欢从嘈杂的环境中观看视频的广播公司来说意义重大。

以前可以通过连接 OBS 和英伟达自己的广播应用程序来使用英伟达在 OBS 中的噪声消除功能，但现在你可以直接在 OBS 中访问该功能，无需任何额外的麻烦。嗯，差不多了。

Nvidia 在 OBS 中的去噪技术仍处于测试阶段，仅在当前的 [OBS beta build](https://obsproject.com/forum/threads/obs-studio-27-release-candidate.141857/) 中可用。测试版还需要你安装 [Nvidia 广播效果 SDK](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/?ncid=afm-chs-44270&ranMID=44270&ranEAID=TnL5HPStwNw&ranSiteID=TnL5HPStwNw-44FfYMNXMjVBzWNaQsQ71A) 才能使用噪点滤镜。但是，一旦即将到来的 OBS 版本 27 发布，Nvidia 噪声消除将工作，除了 RTX GPU 没有额外的要求。

**如何在 OBS 中启用 Nvidia 噪声消除:**

1.  在 OBS 中，右键单击您的音频源并选择**“过滤器”**
2.  在滤镜窗口中，点击左下角的**“+”**，然后从列表中选择**“噪声抑制”**。
3.  命名过滤器。
4.  从方法下拉菜单中选择**“NVIDIA 噪声消除”**。
5.  调整强度设置。
6.  关闭过滤器窗口。

创意 app 优化，OBS 中的原生 Nvidia 降噪，以及所有的 [其他新特性](https://www.nvidia.com/en-us/geforce/news/mortal-shell-ray-tracing-dlss-game-ready-driver/?ncid=afm-chs-44270&ranMID=44270&ranEAID=TnL5HPStwNw&ranSiteID=TnL5HPStwNw-TNdieihhXqJj7K061VGZ6w) 在安装 Nvidia GeForce Experience 版本 3.220.32 后即可使用。该更新将在您下次运行 GeForce Experience 应用程序时自动安装，或者您可以在此处 下载最新版本的安装程序。