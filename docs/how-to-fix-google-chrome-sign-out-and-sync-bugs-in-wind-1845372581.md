# 如何修复 Windows 10 中谷歌 Chrome 登出和同步的 bug

> 原文：<https://lifehacker.com/how-to-fix-google-chrome-sign-out-and-sync-bugs-in-wind-1845372581>

Windows 10 2020 年 5 月的更新让包括我在内的一些用户使用 Chrome 变得更加困难。几个月来，人们报告说，在 Windows 10 上使用 Chrome 时，他们的谷歌账户被不必要的注销，以及由于删除 cookies 而导致的移动设备和 PC 之间的同步问题。

Watch

谷歌和微软都意识到了这些漏洞，但还没有正式的修复方法。幸运的是，有几个变通办法可以帮助您解决这两个问题。这两个都不能保证有效，但是我成功地修复了我的桌面上的 Chrome 问题，其他用户也报告了类似的积极结果。

第一个修正来自最初由 [TechDows](https://techdows.com/2020/10/windows-10-2004-bug-broke-chrome-fix.html) 报道的一个论坛帖子。它涉及从 Windows 10 的任务调度器中查找和删除任务，以阻止你的电脑退出 Chrome 并删除你的 cookies:

1.  在 Windows 开始菜单搜索栏中输入**“PowerShell”**。
2.  **在搜索结果中右键点击** PowerShell，选择**“以管理员身份运行”**
3.  在 Powershell 中键入或粘贴以下命令，然后按下**回车键**来运行它。(如果这样不行，试试直接从 [TechDows 的网站](https://techdows.com/2020/10/windows-10-2004-bug-broke-chrome-fix.html) 复制粘贴。):`Get-ScheduledTask | foreach { If (([xml](Export-ScheduledTask -TaskName $_.TaskName -TaskPath $_.TaskPath)).GetElementsByTagName(“LogonType”).'#text' -eq "S4U") { $_.TaskName } }`
4.  运行该命令后，记下 PowerShell 中列出的任何任务。(如果没有列出任何任务，则下拉至下面的下一组步骤，尝试另一种解决方法)。
5.  接下来，通过从开始菜单中搜索**“任务调度器”**打开任务调度器。
6.  在“任务计划程序”窗口中，查找 PowerShell 中列出的任务。
7.  点击突出显示该任务，然后**右键单击**并选择**的“删除”。**"重复执行 PowerShell 命令后列出的所有任务。

任务调度程序修复为我工作，和它*应该*为你工作。如果不行，有一个更老的解决方法可能会有帮助:

1.  在开始菜单搜索栏中输入**“事件查看器”**，点击“事件查看器”运行应用程序
2.  进入 **Windows 日志>应用和服务>微软> Windows > Crypto-DPAPI >操作**
3.  如果你看到任何错误，然后关闭所有浏览器窗口。
4.  按下 **Windows 键+ L** 锁定您的电脑。
5.  解锁你的电脑，然后加载浏览器。

如果这也不起作用，或者你在日志中没有看到任何错误，下一步是尝试卸载 2020 年 5 月的更新，这是我们在本指南 中带你通过 [完成的任务。](https://lifehacker.com/how-to-undo-and-prevent-windows-updates-1836420965)

[[9 to 5 谷歌](https://9to5google.com/2020/10/12/google-chrome-windows-10-may-update-issues)