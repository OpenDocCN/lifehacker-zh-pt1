# 使用“Ticker”获取股票信息，无需额外的废话

> 原文：<https://lifehacker.com/use-ticker-to-get-stock-info-without-the-extra-crap-1846198236>

即使热门次热门被 [吞没陷入混乱](https://www.reddit.com/r/wallstreetbetstest/)梦想游戏巅峰《登月》被蒸发，这并不意味着你不应该关注股市。我不会推荐交易迷因，但观察你所关注的股票的总体状态从来都不是一件坏事。



为此，我通常会跳到 [雅虎财经](https://finance.yahoo.com/) ，但我承认，我讨厌仅仅为了看股票就打开浏览器。这就是为什么我很高兴偶然发现了 [**Ticker**](https://github.com/achannarasappa/ticker) ，一个方便的命令行程序，你可以用它来得到*只是*价格，而没有多余的废话。这需要一点配置，但它是您在日常生活中让它在后台运行的完美选择。

首先，下载适用于您的操作系统的 [预编译二进制文件](https://github.com/achannarasappa/ticker/releases) (适用于我的 64 位 Windows PC 的“windows-amd64”)。将它解压缩到系统中的任意位置，然后在程序所在的位置启动命令提示符(或终端)。

S 暗示输入`ticker -w`，后跟你关心的股票的逗号分隔名称。因此，如果你热衷于垂死的迷因股票，你可以输入:`ticker -w gme,koss,expr,amc,bb,doge-usd,xrp-usd`

默认情况下，您会得到如下所示的输出:

你还可以添加额外的标志，以获得更多关于你正在~~追踪的~~股票的信息。例如，在这里输入...

`ticker -w gme,koss,expr,amc,bb,doge-usd,xrp-usd —show-fundamentals —show-separator —show-summary`

...g 给你一个更漂亮(和更多信息)的布局:

F 或者我们当中的超级痴迷者，你也可以创建一个. YAML 文件——一个在应用加载时加载的简单配置文件——你可以在其中设置你的配置选项、你关心的股票、*和*你可能购买的股票数量(以及价格)。这使得 Ticker 更加有用，因为您可以直接从命令行跟踪您的投资组合。

因此，使用 Ticker 的 GitHub 上的示例，我在与应用程序相同的目录中创建了一个简单的 ticker.yaml 文本文件。然后，我将它重命名为. ticker.yaml，并在没有额外标志的情况下启动了 ticker——当我与应用程序位于同一目录时，只需在命令提示符下键入“Ticker”。给了我这个:

可爱！我的假股票涨了！虽然 Ticker 需要一点配置来使它最适合你，但它需要几分钟来设置。一旦你做到了这一点，只需加载一个小小的应用程序就可以比浏览器(以及你所有的标签)更容易地查看你的股票。现在，去致富吧——对你持有 20 年的指数基金进行合理投资。