# 如何防止你的AMD处理器自动超频

> 原文:[https://life hacker . com/how-to-prevent-your-amd-processor-from-automatically-ov-1848764075](https://lifehacker.com/how-to-prevent-your-amd-processor-from-automatically-ov-1848764075)

如果你正在摇动台式电脑中的AMD组件，花点时间确保你的CPU不会无意中超频。最近AMD显卡驱动程序更新中的一个bug会自动触发AMD CPUs上的“自动超频”选项，即使用户没有明确打开它。

Watch

AMD在给 [Tom的硬件](https://www.tomshardware.com/news/amd-confirms-its-gpu-drivers-are-overclocking-cpus-without-asking) 的声明中确认了这个bug，但是到目前为止还没有官方的修复发布，尽管 [很多AMD用户都在经历这个问题](https://old.reddit.com/r/Amd/comments/tx1zse/amd_confirms_its_gpu_drivers_are_overclocking/) 。这使得任何拥有AMD CPU和GPU的人都面临不必要的超频风险。(注意，这只适用于使用AMD CPU *和* GPU的用户。配备英特尔CPU和AMD GPU或AMD CPU和Nvidia GPU的平台没有风险。)

## 为什么自动超频有风险

一些用户选择超频他们的CPU来挤出更多的处理能力。虽然超频*可以*让你的电脑更快，但如果操作不当，它也会让处理器过热，有可能对CPU和其他组件造成不可挽回的损害。通常情况下，用户必须访问和编辑他们PC的BIOS设置来改变他们的CPU的时钟速度，但AMD的自动超频功能可以让你直接从Windows桌面上做到这一点。虽然这对那些超频的人来说更方便，并且防止你潜在地搞砸你的BIOS设置，但这个决定似乎适得其反。

一些用户还担心不必要的超频会影响他们的CPU保修。AMD对超频CPU的保修无效，这使得自动超频选项的增加更加奇怪。公平地说，除非用户承认，否则很难证明CPU超频，但希望该公司在这种情况下会对其服务条款做出例外。

虽然我们现在不太担心你的AMD CPU的保修，但如果你不想超频，你还是应该确保它不会超频。

## 如何修复bug

最安全的选择是避免游戏、直播或视频编辑等CPU密集型任务，直到AMD发布一个修补程序来解决这个问题。然而，一些用户正在安装名为 [的第三方软件，镭龙软件瘦身版](https://github.com/GSDragoon/RadeonSoftwareSlimmer) 也是为了规避这个问题。这是一个开源应用程序，从AMD的驱动程序中删除了多余的功能和其他不必要的臃肿——包括自动超频功能。在上面链接的GitHub页面上可以找到安装该软件的说明，但是要注意:AMD还没有正式认可它作为一个解决方案，所以风险自担。