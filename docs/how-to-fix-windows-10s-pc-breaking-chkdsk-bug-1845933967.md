# 如何修复 Windows 10 破坏电脑的“chkdsk”错误

> 原文：<https://lifehacker.com/how-to-fix-windows-10s-pc-breaking-chkdsk-bug-1845933967>

谁会想到 Windows 10 中更有用的故障诊断工具之一——good ol '[*【chkdsk*](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/chkdsk)——本身会被包裹在一个可能让你的 PC 瘫痪的漏洞中。当然不是我，因为“检查磁盘”命令通常用于扫描和*修复文件系统(和相关元数据)的*错误。

Watch

根据本月早些时候发布的 Windows 10 更新 [KB4592438](https://support.microsoft.com/en-us/help/4592438/windows-10-update-kb4592438?ranMID=24542&ranEAID=kXQk6*ivFEQ&ranSiteID=kXQk6.ivFEQ-gNniRcezVgFvC9IFeHiCmA&epi=kXQk6.ivFEQ-gNniRcezVgFvC9IFeHiCmA&irgwc=1&OCID=AID2000142_aff_7593_1243925&tduid=(ir__ynhpbocke9kfq06ekk0sohzibv2xse2xzp23cuw600)(7593)(1243925)(kXQk6.ivFEQ-gNniRcezVgFvC9IFeHiCmA)()&irclickid=_ynhpbocke9kfq06ekk0sohzibv2xse2xzp23cuw600) ，该更新引入的错误可能会导致个人电脑出现一些危险问题。正如微软所描述的:

*“少数安装了此更新的设备报告说，当运行 chkdsk /f 时，他们的文件系统可能会损坏，并且设备可能无法启动。”*

如果我必须按严重程度排列典型的计算机问题，我会说“一个实际上破坏你的系统而不是帮助你解决问题的故障诊断工具”会排在我的列表的最前面。微软声称已经修复了这个问题，所以请确保你已经安装了 Windows Update 中所有可用的东西，以确保你不会被这个令人沮丧的错误所困扰。在那之后，等待，因为官方的修复将自动推出到您的系统。

### 如果 chkdsk 已经破解了你的系统怎么办？

假设你正盯着一个系统，它拒绝像平常一样启动，不要惊慌。或者，更确切地说，你可能已经*恐慌了，所以你已经把大部分压力从身体里释放出来是件好事。有*是*对这个问题的修复，甚至如果你不能进入 Windows 10 用任何延迟更新来解决它。正如微软所描述的:*

> 1.  *After several startup failures, the equipment should automatically start and enter the **recovery console** .*
> 2.  *Select **advanced option** .*
> 3.  *Select **command prompt** from the action list.*
> 4.  *Once the **command prompt** is opened, type: **chkdsk/f***
> 5.  *Allow **chkdsk** to finish scanning, which may take a little time. When finished, type: **exit***
> 6.  *The device should be able to start as expected now. If you restart and enter the **recovery console** , select **to exit and continue to enter Windows 10** .*

一旦你回到 Windows 10，坚持住。微软将在未来几天部署针对 chkdsk 的补丁，所以我会推迟运行 T2 的 chkdsk，至少要到 T4 的周末。

另外，关于这一点还有一句话:一般来说，在没有采取一些预防措施的情况下，您应该避免运行触发这个 bug 的特定命令— *chkdsk /f* 。这个命令定位*，而*修复它发现的错误。如果我是你，我会先运行一个普通的 *chkdsk【盘符】*命令来扫描你的系统。如果或当遇到任何错误时，使用类似于[**Macrium Reflect**](https://lifehacker.com/back-up-and-clone-your-hard-drive-with-macrium-reflect-1825289970)的工具制作您的驱动器的完整映像或克隆(以防万一)。然后，尝试运行 *chkdsk /f* 。如果之后你没有遇到任何问题，那太好了。如果您这样做了，您仍然可以保留您的数据和/或能够将您的系统恢复到更可用的状态。

和往常一样，请记住您不需要在 SSD 上运行 *chkdsk /r* ，因为与机械硬盘相比，这是完全不必要的。如果你怀疑你的电脑驱动器有机械问题，而不是文件系统问题， *chkdsk* 不会有太大帮助。相反，可以考虑通过运行 [智能报告](https://lifehacker.com/how-to-check-if-your-hard-drive-is-failing-1835065626) 来检查其健康状况。