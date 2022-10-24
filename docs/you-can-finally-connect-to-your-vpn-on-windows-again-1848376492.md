# 您终于可以再次连接到Windows上的VPN了

> 原文:[https://life hacker . com/you-can-finally-connect-to-your-VPN-on-windows-again-1848376492](https://lifehacker.com/you-can-finally-connect-to-your-vpn-on-windows-again-1848376492)

如果你上周安装了最新的Windows Server更新，你可能会注意到一些令人沮丧的事情— [你的VPN无法连接到Windows](https://www.xda-developers.com/windows-update-causing-issues-vpn/) 。该问题主要针对Windows VPN客户端，但会影响多个VPN设备，如SonicWall、WatchGuard防火墙和Cisco Meraki。如果你卸载了这些更新，或者只是听到这个消息后避免更新，你会很高兴地得知微软终于修补了这个漏洞。

Watch

在微软1月11日 发布更新后，这个漏洞似乎主要影响运行Windows 10和Windows 11 [的机器。由于这些更新是2022年第一个补丁的一部分，它没有为微软今年设定一个好的基调。(](https://www.bleepingcomputer.com/news/microsoft/new-windows-server-updates-cause-dc-boot-loops-break-hyper-v/) [正如一位Redditor如此优雅地说的](https://www.reddit.com/r/sysadmin/comments/s1oqv8/comment/hs9lgkt/?utm_source=share&utm_medium=web2x&context=3) ，“为了他妈的微软。”)

说到Reddit，我们首先是通过该网站的r/sysadmin了解到这个问题的。 [用户In_Gen发布了](https://www.reddit.com/r/sysadmin/comments/s1oqv8/kb5009543_january_11_2022_breaks_l2tp_vpn/) 关于更新KB5009543和KB5008876，以及版本如何打破对两台Windows 10笔记本电脑的VPN支持。卸载更新后，他们的VPN再次连接，这表明该漏洞与新的微软补丁有内在联系。

虽然据报道VPN问题仅限于Windows 10和Windows 11，但微软今天为几乎所有受支持的Windows版本发布了补丁，包括Windows 7。这些更新修复了除VPN连接之外的其他问题，并且可能会因您运行的Windows版本而异。您可能会看到以下修复的组合:

*   解决了可能导致包含供应商ID的IP安全(IPSEC)连接失败的已知问题。使用第2层隧道协议(L2TP)或IP安全Internet密钥交换(IPSEC IKE)的VPN连接也可能受到影响。
*   解决了一个问题，该问题可能会阻止使用弹性文件系统(ReFS)格式化的可移动介质装入，或者可能会导致可移动介质以原始文件格式装入。安装2011年1月日的Windows更新后出现此问题。
*   解决了在域控制器(DC)上安装Jan. 11 更新后可能导致Windows服务器意外重启的已知问题。
*   解决了当您进行多个属性更改时，在轻型目录访问协议(LDAP)修改操作期间无法正确写入Active Directory (AD)属性的问题。

## 如何安装Windows VPN补丁

如果您的机器上有更新，请进入到**开始** > **设置** > **Windows更新** (Windows 11)或**开始>设置** > **更新&安全** > **Windows更新** (Windows 10)。在此页面上，您可以检查任何可用的更新。

如果今天的更新不存在，你可以从 [XDA开发者](https://www.xda-developers.com/microsoft-fixes-windows-vpn-issues/) 手动下载。您也可以使用此页面作为资源来查看您是否有合适的更新；检查您的Windows版本，并查看更新名称是否与您的版本相同。例如，Windows 11的VPN补丁名为KB5010795— 如果你在运行Windows 11的电脑上没有看到，你最好手动下载更新。

【 [XDA 开发商](https://www.xda-developers.com/windows-update-causing-issues-vpn/) 】