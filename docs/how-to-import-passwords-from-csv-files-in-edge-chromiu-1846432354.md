# 如何从导入密码？边缘铬中的 CSV 文件

> 原文：<https://lifehacker.com/how-to-import-passwords-from-csv-files-in-edge-chromiu-1846432354>

微软正在测试使用逗号分隔值将密码和登录信息导入 Edge Chromium 的能力。CSV)文件。Edge 已经允许你从其他浏览器或通过同步密码管理器应用程序数据导入密码，但简化的。CSV 选项最近出现在 Edge Canary 版本 90 中。

Watch

顾名思义，CSV 格式中的所有信息都用逗号分隔。在这种情况下，登录数据将包括一个站点的 URL、与该网站相关联的用户名以及帐户的密码— ，所有这些都被分成部分。一些密码管理器允许你将数据导出为。CSV 文件，或者你可以在你最喜欢的电子表格应用中创建自己的文件，比如 Excel 或 Google Sheets，或者用文本编辑器比如记事本。您可以使用密码保护和加密。CSV 文件也是。

在微软添加。CSV 选项，用户必须使用复杂的变通办法来导入。CSV 数据到边缘 [桌面](https://support.dashlane.com/hc/en-us/articles/202625132-How-to-import-passwords-in-a-CSV-file) 和 [安卓](https://techdows.com/2021/02/import-passwords-from-csv-to-edge-chromium-via-microsoft-authenticator.html) 。如果你不想下载 Edge C anary，这些技巧仍然有效——毕竟它没有公开版稳定。在某种程度上。CSV 导入选项应该会成为稳定版本，但是我们将向您展示如何在早期试用该功能。

### 如何导入？ CSV 密码文件到边缘

在导入. CSV 文件之前，您需要在 Edge Canary 的实验标志菜单中启用该功能。

1.  从 [Edge Insiders 频道](https://www.microsoftedgeinsider.com/en-us/download) 下载安装 Edge Canary。如果您已经使用 Edge Canary，请确保更新到版本 90 或更新版本。
2.  开边金丝雀。
3.  转到**edge://flags/# password import**。
4.  从下拉框中选择**“启用”**。
5.  当提示保存并应用更改时，单击**“重启”**。浏览器将重新启动。

现在可以导入了。CSV 文件通过密码菜单:

1.  在边缘金丝雀中，点击**“..”右上角的**图标。
2.  转到**设置>配置文件>密码。**
3.  点击**“…”**旁边的**“保存的密码。”**
4.  选择**“导入密码”**
5.  从下拉框中选择**“CSV 文件”**，确保勾选**“密码”**框。
6.  点击**“选择文件”**
7.  使用文件资源管理器窗口查找并选择您的 CSV 文件。

[ [Techdows](https://techdows.com/2021/03/microsoft-edge-chromium-gets-native-password-import-feature.html)