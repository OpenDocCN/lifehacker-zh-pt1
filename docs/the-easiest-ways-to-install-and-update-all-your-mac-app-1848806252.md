# 安装和更新所有 Mac 应用程序的最简单方法

> 原文：<https://lifehacker.com/the-easiest-ways-to-install-and-update-all-your-mac-app-1848806252>

一旦你已经 [设置了你全新的 Mac](https://lifehacker.com/how-to-set-up-your-macbook-from-scratch-1825920271) ，或者在你的机器上完成了 macOS 的全新安装，你可以通过自动化应用程序安装和更新过程来为自己节省大量时间。如果你曾经在 Windows 上使用过 Ninite，我们将向你展示如何在 Mac 上使用它的替代品。

Watch

## 适用于大多数人的快速应用程序安装:macapps.link

为了加快应用程序在 Mac 上的安装速度，访问 [macapps.link](https://macapps.link) 。它的工作方式类似于 Windows 上的 Ninite。您查看应用程序列表，选择您需要的应用程序，然后单击顶部的安装按钮。网站生成一个代码，你可以复制并粘贴到 Mac 的终端应用中。当运行该命令时，您选择的所有应用程序将被逐一下载并安装。当你打开刚刚安装的付费应用时，除了粘贴许可密钥之外，你不需要做任何其他事情。

Macapps.link 在其网站上有一个很长的应用程序列表，但是它没有你需要的所有*应用程序，所以你仍然必须手动下载并安装一些。此外，虽然该服务从未有过任何恶意活动的报告，但它通过运行“ [curl | bash](https://sysdig.com/blog/friends-dont-let-friends-curl-bash/) ”脚本来工作，这可能是一种不太安全的从互联网下载应用程序和链接的方法。如果你想 100%安全，考虑以下替代方案。* 

## 更安全的选择:自制

如果你对在 Mac 上使用终端 来安装应用程序感到舒适，那么自制软件将会让事情变得简单。你唯一需要的技术诀窍是访问家酿网站并在终端中复制粘贴一些命令。

家酿是一种安装命令行工具和每个人都使用的基于 GUI 的应用程序的安全方式。V 访问 [自制软件网站](https://brew.sh) ，复制**安装自制软件**下的命令。是这个:

`/bin/bash -c "$(curl -fsSL` [`https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)`](https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)) `"`

在 Mac 上打开终端，粘贴命令，然后按回车键。这将开始在您的计算机上安装家酿。该过程完成后，您可以使用简单的命令来安装和卸载应用程序。

如果你正在寻找安装命令行工具，其中包括有用的东西，如 YouTube 下载程序，访问 [自制公式](https://formulae.brew.sh/formula/) 页面。你可以点击你需要的工具名称，复制**安装命令**旁边的代码。在终端中运行此命令，开始安装任何工具。

同样，你可以在 [家酿木桶](https://formulae.brew.sh/cask/) 页面找到大多数人使用的应用，按照同样的步骤安装你最喜欢的应用。Iinstall 命令看起来像这样:

`brew install yt-dlp`

这将在您的 Mac 上安装一个 YouTube 下载程序。你可以把 yt-dlp 替换成你要安装的 app 的名称。要删除这些应用程序，使用此命令(j 必须用您要删除的应用程序的名称替换 ) :

`brew uninstall yt-dlp`

安装和删除应用程序都可以直接从终端完成。

## 轻松更新您的应用

如果你没有使用苹果应用商店的应用程序，手动更新每个应用程序可能会很痛苦(T2)。如果你用自制软件安装了所有应用程序，那么有一个简单的命令可以让你一次性更新所有这些应用程序。首先，安装 brew-buck-upgrade 命令行工具以访问更新命令。安装 Homebrew 后，打开 Mac 上的“终端”,粘贴以下命令:

`brew tap buo/cask-upgrade`

接下来，运行以下命令一次性更新所有应用程序:

`brew cu -af`

这将自动检查通过自制软件安装的所有应用程序的更新，并逐个安装这些更新——从现在起大约每周运行一次命令，定期检查更新。

如果你不喜欢使用自制软件或者如果你的应用程序不能用它安装、可以考虑试试、、 [MacUpdater](https://www.corecode.io/macupdater/) 、。它会自动扫描您的 Mac 上已安装的应用程序，并帮助您轻松下载和安装更新。你可以免费扫描所有应用，并一次性支付 15 美元，让应用为你管理应用更新。