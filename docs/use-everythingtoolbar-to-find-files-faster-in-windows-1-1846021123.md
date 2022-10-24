# 在 Windows 10 中使用“EverythingToolbar”更快地查找文件

> 原文：<https://lifehacker.com/use-everythingtoolbar-to-find-files-faster-in-windows-1-1846021123>

我没有经常使用 Windows 10 的搜索功能，因为我觉得它不是很有用。默认情况下，在紧急情况下查找应用程序或跳到设置窗口很方便，而不必浏览选项树，但这就是我与它的互动。所以我愿意放弃这个功能，把它变成我电脑上一个非常强大的搜索工具。



不过，要做到这一点，我需要一点帮助。我将使用刚刚发布的[**Everything toolbar**](https://github.com/stnkl/EverythingToolbar)项目，你可以用它来用 Voidtool 广受欢迎的“ [Everything](https://www.voidtools.com/) ”搜索工具取代 Windows 10 的传统搜索栏。

要开始，你需要下载并安装 [所有的](https://www.voidtools.com/) 。这应该是不言自明的。然后您将下载并安装 EverythingToolbar，这需要您运行一个简单的。具有管理员访问权限的 CMD 文件。然后右键单击任务栏(可能两次)激活新工具栏，然后禁用标准搜索工具栏，拖动所有工具栏来替换它，如下所示:

EverythingToolbar 的一个缺点是，如预期的那样，按 Windows 键会弹出标准的开始菜单，输入任何内容都会启动 Windows 10 的默认搜索，而不是 EverythingToolbar。不过，这是意料之中的。(如果你愿意的话，我想你可以将所有工具栏的热键 **Windows 键+ Alt + S** 重新映射到实际的 Windows 键上，但是每次你想启动它的时候，你都必须点击开始菜单。选择，选择。)

在 EverythingToolbar 的选项中，你会发现通过大小写、路径和全词进行匹配的能力，以及一个让你使用 [正则表达式](https://help.relativity.com/9.5/Content/Relativity/Regular_expressions/Searching_with_regular_expressions.htm)——高级模式，真的。您也可以通过右键单击所有工具栏的搜索字段来访问这些设置。

最后，我想提醒大家注意该实用程序的“规则”部分，它允许您定义自定义的“打开方式”命令。这样，您可以根据您在搜索中使用的任何正则表达式，定义不同的应用程序来打开您搜索的文件和文件夹。

这个功能肯定属于“超级用户”的范畴，但这只是一切——以及一切工具栏——比 Windows 10 默认的开始菜单搜索有用得多的另一种方式。当然，如果你不想弄乱额外的实用程序，你也可以深入挖掘 Windows 10 来实现类似的功能:访问**设置>搜索>搜索窗口**，并打开**增强模式**，这可以让你快速搜索*硬盘上的一切*，而不仅仅是 Windows 10 库或桌面上的文件。