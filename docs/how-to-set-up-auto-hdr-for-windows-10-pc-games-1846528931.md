# 如何为 Windows 10 电脑游戏设置自动 HDR

> 原文：<https://lifehacker.com/how-to-set-up-auto-hdr-for-windows-10-pc-games-1846528931>

微软正在为 Windows 10 添加自动 HDR 功能。新设置借鉴了 Xbox Series X/S，为 DirectX 11 和 DirectX 12 游戏增加了 HDR(高动态范围)颜色和亮度级别，否则这些游戏只有 SDR(标准动态范围)。 [微软指出](https://devblogs.microsoft.com/directx/auto-hdr-preview-for-pc-available-today/) 它的自动 HDR 技术将无法与 HDR 本土的视觉效果相匹配，但使用这一功能仍然会带来更丰富多彩和更有活力的 PC 游戏——甚至那些没有考虑到 HDR 的旧游戏也会得到提升。



自动 HDR 在最新的 Windows Insider 开发频道版本(build 21337)中可用，但将在未来几周内推出 Windows 10 的稳定版本。以下是如何加入 Insider 计划并安装新的开发人员版本，以便尽早体验 HDR 车展:

1.  进入 [Windows Insider 程序主页](https://insider.windows.com/en-us/) 。
2.  点击**“注册”**，然后使用您的 Microsoft 帐户登录。
3.  按照屏幕上的说明安装 Windows Insider Dev Channel build 21337(或更高版本)。

同样，加入 Windows Insider 计划只有在您想尽早尝试自动 HDR 时才有必要。然而，所有用户都需要一台 HDR 显示器，以便在新的显示设置可用时使用它。如果你的硬件支持 HDR，以下是如何在 Windows 10 上启用自动 HDR 的方法:

1.  右键- c 点击你的桌面屏幕，选择**“显示设置”**(或者打开开始菜单，进入**设置>系统>显示**)。
2.  在显示菜单中，点击**“Windows HD 颜色设置”**
3.  确保**“使用 HDR”**开关打开，然后向下滚动并启用**“自动 HDR”(**注:如果**【使用 HDR】****【自动 HDR】**灰显或缺失，则您的显示器不支持 HDR。 **)**
4.  关闭设置窗口。
5.  下次你玩电脑游戏时，如果游戏支持自动 HDR 功能，它就会自动启动。

微软还创建了一个特殊的“分屏”模式，让你实时看到自动 HDR 带来的变化。启用分屏自动 HDR 在一个显示器上显示非 HDR 游戏，在另一个显示器上显示自动 HDR 增强的视觉效果。自然，渲染游戏两次会影响性能，会降低你的电脑速度；微软表示，分屏模式是为想查看自动 HDR 增强功能的开发者设计的，但所有 Windows 内部人士如果好奇也可以尝试一下

1.  以管理员身份运行命令提示符。
2.  运行此命令启用分屏自动 HDR: *`reg add HKLM\SYSTEM\CurrentControlSet\Control\GraphicsDrivers /v AutoHDR.ScreenSplit /t REG_DWORD /d 1`*
3.  运行此命令将其禁用: *`reg delete HKLM\SYSTEM\CurrentControlSet\Control\GraphicsDrivers /v AutoHDR.ScreenSplit /f`*

[ [多边形](https://www.polygon.com/22336512/auto-hdr-for-pc-preview-program-feature-support-access-windows) ]