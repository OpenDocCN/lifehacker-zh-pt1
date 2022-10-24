# 伙计，为你的戴尔电脑获取安全更新

> 原文:[https://life hacker . com/dude-get-a-security-update-for-your-Dell-PC-1846828180](https://lifehacker.com/dude-get-a-security-update-for-your-dell-pc-1846828180)

你还持有2009年左右的技术股吗？也许是一个旧的CPU或主板，放在你壁橱里的一个盒子里，以防你需要备份？戴尔怎么样？如果你或你关心的人碰巧还在使用从巴拉克·奥巴马开始他的第一个任期到现在的任何时候生产的戴尔电脑，你应该检查一下，以确保你不需要刚刚放弃的重要安全更新。

Watch

该更新修复了一个与 *dbutil_2_3.sys* Windows驱动程序有关的漏洞，戴尔称，“当您使用固件更新实用程序包、戴尔命令更新、戴尔更新、外星人更新、戴尔系统清单代理或戴尔平台标签时，包括使用任何戴尔通知解决方案来更新您系统的驱动程序、BIOS或固件时，该漏洞可能已安装在您的戴尔Windows操作系统上。”

强烈建议您使用方便的戴尔实用程序删除上述驱动程序，并安装更新的软件，以防止不需要的驱动程序在将来任何时候再次出现在您的系统上。戴尔称，该漏洞“可能导致权限升级、拒绝服务或信息泄露”，其严重程度在CVSS得到了8.8分(满分10分)。(尽管值得注意的是，攻击者需要对自己的计算机进行“本地认证访问”才能利用这一漏洞——无论是亲自访问，还是通过某种恶意软件/网络钓鱼/远程访问利用。)

首先，下载并运行“戴尔安全顾问更新-DSA-2021-088”[实用程序](https://www.dell.com/support/home/drivers/driversdetails?driverid=7PR57) ，它会为您找到并删除 *dbutil_2_3.sys* 。您也可以手动搜索该文件。它可能出现在两个地方之一:

> *   *C:\ Users \ <用户名> \ AppData \ Local \ Temp*
> *   *C:\ Windows \ Temp*

如果或者当你自己找到这个文件时，只需按Shift+Delete键就可以把它清除掉。

您也可以等到5月10日，届时使用任何戴尔的 [内置工具](https://www.dell.com/support/contents/en-us/article/product-support/self-support-knowledgebase/software-and-downloads/download-center/drivers-and-downloads/notifications) (如SupportAssist或戴尔更新)运行常规系统更新，将自动安装并运行“DSA-2021-088”实用程序。无论如何，您都需要运行这些工具中的一个来安装上述较新的固件更新，这将阻止这个较旧的、易受攻击的驱动程序返回到您的系统。

为了简单起见，我可能会等到5月10日。检查并安装戴尔要求您在那一周运行的任何系统更新。如果没有，那么你很幸运，你的系统没有受到影响。(您也可以查看*是否*您受到了影响，在此页面 戴尔列出了 [的380台受影响的电脑中扫描您的特定戴尔系统。)](https://www.dell.com/support/kbdoc/en-us/000186019/dsa-2021-088-dell-client-platform-security-update-for-dell-driver-insufficient-access-control-vulnerability)

为了安全起见，无论您是否在列表中找到您的系统，下周都要运行您的更新工具。拥有你能得到的最新的个人电脑——软件*和固件*,从来没有坏处。所有这一切的一线希望？根据 [戴尔](https://www.dell.com/support/kbdoc/en-us/000186020/additional-information-regarding-dsa-2021-088-dell-driver-insufficient-access-control-vulnerability) 的说法，该公司“到目前为止还不知道这个漏洞被恶意行为者利用了。”因此，这不是一个停止媒体的更新，但仍然是你想要解决的问题。