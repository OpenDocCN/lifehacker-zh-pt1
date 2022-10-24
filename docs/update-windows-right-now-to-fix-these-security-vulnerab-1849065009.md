# 立即更新 Windows 以修复这些安全漏洞

> 原文：<https://lifehacker.com/update-windows-right-now-to-fix-these-security-vulnerab-1849065009>

在理想的世界中，软件没有安全漏洞。代码将被完美地编写，省略系统中任何可能被黑客或其他恶意目的利用的错误或故障。尽管开发人员可能会努力实现这一点，但事实是我们总是会有不完美的软件，这意味着我们总是会有新的安全漏洞需要发现和修补。微软现在已经为 Windows 个人电脑提供了这样的补丁，你应该尽快安装它。



据哔哔声计算机 T3 报道，昨天，6 月 14 日星期二，微软发布了本月的补丁。微软周二的补丁更新可能是意料之中的，但它修补了一些你不应该忽视的严重缺陷。总共有 55 个补丁，但有三个特别标记为“关键:”这些漏洞允许远程 cote 执行，这使得不良行为者有可能操纵和运行您的计算机上的程序。三个关键的安全漏洞是:

*   [CVE-2022-30163](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2022-30163):Windows Hyper-V 远程代码执行漏洞。
*   [CVE-2022-30139](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2022-30139):Windows 轻量级目录访问协议(LDAP)远程代码执行漏洞。
*   [【CVE-2022-30136】](https://portal.msrc.microsoft.com/en-US/security-guidance/advisory/CVE-2022-30136):Windows 网络文件系统远程代码执行漏洞。

此更新中总共修补了 27 个远程代码执行漏洞、12 个特权提升漏洞、11 个信息泄露漏洞、三个拒绝服务漏洞、一个欺骗漏洞和一个安全功能绕过漏洞。您可以 [点击此处查看这些漏洞及其标识符的完整列表](https://www.bleepingcomputer.com/microsoft-patch-tuesday-reports/June-2022.html) 。

然而，这一次最大的修补是针对被称为 Follina 的零日漏洞的补丁。这个被标识为 [CVE-2022-30190](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2022-30190) 的漏洞是在上个月发现的:它允许不良行为者从一个简单的恶意 Word 文档中在受害者的机器上执行 PowerShell 命令。这些文件可以通过通常的渠道共享，如电子邮件，当不知情的用户打开时，发送者可以通过 Windows 微软诊断工具(MSDT)利用 PowerShell 漏洞。

根据哔哔计算机的说法，这一漏洞被用于攻击美国政府机构、乌克兰媒体机构，以及分发 QBot 恶意软件。它包含在 2022 年 6 月的补丁星期二，使这个更新必须安装。然而，有趣的是， [上个月五月的安全补丁](https://lifehacker.com/you-need-to-update-windows-right-now-1848909833) 实际上比六月的更新扑灭了更多的火灾:上周二的补丁解决了总共 75 个漏洞，有三个零日漏洞。

## 如何更新 Windows 以便在您的电脑上安装最新的补丁程序

你的电脑可能会自动安装这些安全更新。但是，为了确保尽快安装，请进入**开始>设置>更新&安全> Windows 更新** (Windows 10)或**开始>设置> Windows 更新** (Windows 11)。允许 Windows 检查任何可用的更新:如果修补程序可用，您将在此处看到它。然后，您只需按照屏幕上的说明将更新下载并安装到您的计算机上。