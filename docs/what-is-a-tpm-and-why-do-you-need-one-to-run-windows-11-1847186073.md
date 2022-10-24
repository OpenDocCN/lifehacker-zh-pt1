# 什么是“TPM ”,为什么运行Windows 11需要TPM？

> 原文:[https://life hacker . com/what-a-TPM-and-why-do-you-need-one-to-run-windows-11-1847186073](https://lifehacker.com/what-is-a-tpm-and-why-do-you-need-one-to-run-windows-11-1847186073)

Windows 11本周正式推出，许多热切的用户正在检查他们的电脑是否可以运行即将推出的微软Windows健康检查应用程序操作系统。然而，一些人惊讶地得知，尽管他们的电脑有了新的高端硬件，但他们的电脑已经“Windows 11就绪”。

Watch

## 什么是TPM？

混淆的主要来源是TPM(可信平台模块)芯片，这是一个不常见的硬件要求，直到现在。TPMs是一个安全组件，可监控您的电脑是否有问题，并可防范潜在的恶意软件和勒索软件攻击。他们还可以在本地安全地存储加密密钥、密码和其他敏感信息。

多年来，TPM一直是Windows 10的“软”要求，但微软正在 [将它们变成Windows 11的“硬”要求](https://www.microsoft.com/en-us/windows/windows-11-specifications#primaryR2) ，以提高Windows 11 PCs的基准数据安全性。用户需要2.0版TPM或更高版本才能运行Windows 11，同时需要一个兼容DirectX 12的GPU一个支持 [英特尔](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-intel-processors)[AMD](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-amd-processors)或 [高通](https://docs.microsoft.com/en-us/windows-hardware/design/minimum/supported/windows-11-supported-qualcomm-processors) 的CPU4 GB内存；和至少65GBs的存储空间。

## 不是每个人都需要升级

微软希望Windows 11比以前的Windows版本更能抵御恶意软件、勒索软件和其他网络安全威胁。该公司依靠2.0 TPMs和 [UEFI安全引导](https://docs.microsoft.com/en-us/windows-hardware/design/device-experiences/oem-secure-boot) 等技术来实现这一目标，但TPMs可能不是用户在购买或构建新PC时考虑的组件。这可以解释为什么有些电脑“没有做好Windows 11的准备”，即使其余的硬件符合Windows 11的要求。

然而，可能许多用户已经有了TPM，而没有意识到这一点。过去几年发布的许多(但不是所有)CPU都内置了TPM模块，需要在计算机的BIOS设置中启用。默认情况下，Windows会关闭这些功能，如果它不处于活动状态，当Windows运行状况检查扫描您的硬件时，它可能不会显示出来。访问和启用您的TPM—甚至您需要激活的设置的名称—在不同的制造商之间有很大的不同。有关正确的步骤，请咨询您的CPU 或主板制造商。

## 如果没有TPM芯片该怎么办

如果你没有TPM，下一个选择是在网上买一个自己安装。不幸的是，这对于普通用户来说很困难。

首要任务是找到兼容的TPM。有些CPU不支持TPMs，所以在购买之前一定要研究一下...o r我应该说， *如果你能*买一个——[黄牛党正在囤积TPM芯片](https://www.windowscentral.com/psa-scalpers-are-hoarding-tpm20-modules) 并以远高于建议零售价*的价格出售。通常14-30美元的组件现在要花费100美元以上。没有现在的GPU和CPU市场那么差，但这也不多说。*

*如果你找到一个价格合理的兼容的2.0 TPM，那么你必须打开你的PC并访问主板来手动安装。这对于一些个人电脑(尤其是笔记本电脑)来说将是一个挑战，而在某些平板电脑和混合设备(如微软Surface)上是不可能的。再次，在你购买之前做好调查。*

*如果你不能为你当前的电脑购买和安装TPM，那么如果你想升级到Windows 11，你需要购买或建造一台新的电脑。谢天谢地，微软打算 [支持Windows 10到2025年10月14日](https://lifehacker.com/dont-install-the-leaked-windows-11-build-1847115234) ，所以没有马上升级的压力。希望TPM市场——以及整个技术硬件市场——会在那之前稳定下来，升级不会这么麻烦。*

*[]*