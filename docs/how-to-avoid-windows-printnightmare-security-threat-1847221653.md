# 那些“print nightman”Windows 补丁不工作了，现在该怎么办[更新]

> 原文：<https://lifehacker.com/how-to-avoid-windows-printnightmare-security-threat-1847221653>

微软最近发布了紧急补丁，以修复 Windows 的打印假脱机程序代码中被称为“打印噩梦”的重大零日安全漏洞，但他们没有解决这个问题。安全研究人员发现，即使打了补丁(通过 [TechRadar](https://www.techradar.com/news/microsofts-emergency-printnightmare-patch-doesnt-actually-fix-the-issue-at-all) )，该漏洞仍然存在于几个版本的 Windows 上，使用户容易受到严重的网络安全威胁。



通过利用 PrintNightmare bug，黑客可以控制 PC 并安装恶意软件、勒索软件、窃取或破坏重要数据等，而无需物理接触计算机。你知道，真正的黑帽子。

一些安全专家怀疑 公司在正式发布补丁之前根本没有对其进行测试。无论如何，这对微软来说都是一个坏消息，只会让 PrintNightmare 的崩溃变成一个更大的噩梦——让数百万 Windows 设备处于危险之中。

### **什么是 PrintNightmare？**

PrintNightmare 影响所有版本的 Windows 中的 Windows 打印后台程序，包括安装在个人计算机、企业网络、Windows 服务器和域控制器上的版本。更糟糕的是，由于笨拙的概念证明(PoC)攻击，黑客正在积极利用 PrintSpooler。

Sangfor 的安全研究人员发现了 PrintNightmare 漏洞以及 Windows 打印假脱机服务中的其他几个零日漏洞。该小组创建了 PoC 漏洞，作为即将到来的缺陷演示的一部分。研究人员认为这些漏洞已经被修补，并在 Github 上发布了它们。

事实上，微软在之前的安全更新中修补了一些零日打印假脱机系统的漏洞，但 PrintNightmare 没有修补。虽然 Sangfor 的原始 PringNightmare PoC 不再在 Github 上，但该项目在被拆除之前被复制，有证据表明 PoC 漏洞已被利用。

微软为所有受影响的 Windows 版本发布了紧急安全补丁，包括:

*   Windows 10
*   Windows 8.1
*   Windows 7
*   Windows RT 8.1
*   Windows Server 的众多版本

不幸的是，正如我们现在所知，补丁没有做蹲。幸运的是，Windows 打印假脱机服务*可以暂时禁用*,以防止打印噩梦攻击。

### **立即禁用 Window 后台打印程序服务**

网络管理员可以使用组策略禁用(和恢复)Windows 打印假脱机程序和远程打印，但一般用户需要使用 Powershell 命令将其关闭，这将保护您的电脑免受任何打印噩梦威胁:

1.  使用任务栏或 Windows 开始菜单搜索**“Powershell”**
2.  右键单击 Powershell 并选择**“以管理员身份运行”**
3.  在 Powershell 提示符下，运行以下命令禁用 Windows 打印假脱机程序:`Stop-Service -Name Spooler -Force`
4.  然后运行此命令以防止 Windows 在启动时重新启用后台打印程序服务:`Set-Service -Name Spooler -StartupType Disabled`
5.  在不久的将来，微软的补丁可用并安装到您的 PC 上之前，请禁用您的 Windows 打印后台处理程序服务。安全修补后，您可以使用`Set-Service -Name Spooler -StartupType Automatic`和`Start-Service -Name Spooler commands.`在 Powershell 中重新启用打印假脱机服务

请注意，这是*而不是*长期预防措施，因为即使禁用了打印假脱机服务，漏洞仍然存在。然而，这是目前唯一的选择。为了安全起见，我们建议即使 Microsoft 发布了后续安全更新，也要禁用后台打印程序。一旦确认漏洞已完全修补，您可以重新启用 Print Spooler。

如果有新的补丁发布，我们会再次更新这个帖子。对于大多数 Windows 10 用户来说，进一步的安全更新会自动显示，但你也可以在**设置>更新&安全> Windows 更新>检查更新中手动检查新的补丁。**Windows 7 等旧版本的用户需要从微软的安全更新指南中手动下载并安装补丁。

* * *

*本文最初发布于 2021 年 7 月 2 日，并于 2021 年 7 月 7 日更新了安装 Windows 紧急安全补丁的说明，并于 2021 年 7 月 8 日再次更新了补丁不起作用的报告。*

[]