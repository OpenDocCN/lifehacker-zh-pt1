# 什么是“TPM ”,为什么运行 Windows 11 需要 TPM？

> 原文：<https://lifehacker.com/what-is-a-tpm-and-why-do-you-need-one-to-run-windows-11-1847186073>

Windows 11 本周正式推出，许多热切的用户正在检查他们的电脑是否可以运行即将推出的微软 Windows 健康检查应用程序操作系统。然而，一些人惊讶地得知，尽管他们的电脑有了新的高端硬件，但他们的电脑已经“Windows 11 就绪”。

Watch

## 什么是 TPM？

混淆的主要来源是 TPM(可信平台模块)芯片，这是一个不常见的硬件要求，直到现在。TPMs 是一个安全组件，可监控您的电脑是否有问题，并可防范潜在的恶意软件和勒索软件攻击。他们还可以在本地安全地存储加密密钥、密码和其他敏感信息。

多年来，TPM 一直是 Windows 10 的“软”要求，但微软正在 [将它们变成 Windows 11 的“硬”要求](https://www.microsoft.com/en-us/windows/windows-11-specifications#primaryR2) ，以提高 Windows 11 PCs 的基准数据安全性。用户需要 2.0 版 TPM 或更高版本才能运行 Windows 11，同时需要一个兼容 DirectX 12 的 GPU 一个支持 [英特尔](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-intel-processors)[AMD](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-amd-processors)或 [高通](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-qualcomm-processors) 的 CPU4 GB 内存；和至少 65GBs 的存储空间。

## 不是每个人都需要升级

微软希望 Windows 11 比以前的 Windows 版本更能抵御恶意软件、勒索软件和其他网络安全威胁。该公司依靠 2.0 TPMs 和 [UEFI 安全引导](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-secure-boot) 等技术来实现这一目标，但 TPMs 可能不是用户在购买或构建新 PC 时考虑的组件。这可以解释为什么有些电脑“没有做好 Windows 11 的准备”，即使其余的硬件符合 Windows 11 的要求。

然而，可能许多用户已经有了 TPM，而没有意识到这一点。过去几年发布的许多(但不是所有)CPU 都内置了 TPM 模块，需要在计算机的 BIOS 设置中启用。默认情况下，Windows 会关闭这些功能，如果它不处于活动状态，当 Windows 运行状况检查扫描您的硬件时，它可能不会显示出来。访问和启用您的 TPM—甚至您需要激活的设置的名称—在不同的制造商之间有很大的不同。有关正确的步骤，请咨询您的 CPU 或主板制造商。

## 如果没有 TPM 芯片该怎么办

如果你没有 TPM，下一个选择是在网上买一个自己安装。不幸的是，这对于普通用户来说很困难。

首要任务是找到兼容的 TPM。有些 CPU 不支持 TPMs，所以在购买之前一定要研究一下...o r 我应该说， *如果你能*买一个——[黄牛党正在囤积 TPM 芯片](https://www.windowscentral.com/psa-scalpers-are-hoarding-tpm20-modules) 并以远高于建议零售价*的价格出售。通常 14-30 美元的组件现在要花费 100 美元以上。没有现在的 GPU 和 CPU 市场那么差，但这也不多说。*

*如果你找到一个价格合理的兼容的 2.0 TPM，那么你必须打开你的 PC 并访问主板来手动安装。这对于一些个人电脑(尤其是笔记本电脑)来说将是一个挑战，而在某些平板电脑和混合设备(如微软 Surface)上是不可能的。再次，在你购买之前做好调查。*

*如果你不能为你当前的电脑购买和安装 TPM，那么如果你想升级到 Windows 11，你需要购买或建造一台新的电脑。谢天谢地，微软打算 [支持 Windows 10 到 2025 年 10 月 14 日](https://lifehacker.com/dont-install-the-leaked-windows-11-build-1847115234) ，所以没有马上升级的压力。希望 TPM 市场——以及整个技术硬件市场——会在那之前稳定下来，升级不会这么麻烦。*

*[]*