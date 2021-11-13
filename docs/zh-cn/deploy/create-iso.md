# 创建 Office ISO

创建 Office ISO 文件允许你与其他人分享 Office，或者用于大批量、多次安装。

为了获得更好的体验，请确保你始终从[官方网站](https://otp.landian.vip/)下载了最新的 with runtime 版本的 Office Tool Plus，有时候我们会更新 .NET Runtime，这些文件不会随着 Office Tool Plus 的自动升级而更新，需要手动重新下载。

我们建议您一个月更新一次 Office ISO，与 Office 更新频率保持一致，每个月的第二个星期二为 Office 固定的补丁日。

Office ISO 创建完成后，我们建议您验证一下 ISO 是否和你预期的一样能够正常使用。

::: tip 提示
使用 with runtime 版本的 Office Tool Plus 允许你在没有安装 .NET Desktop Runtime 的情况下直接运行程序，这对大批量安装非常有帮助。
:::

## 下载 & 创建 Office ISO

打开 Office Tool Plus，在部署页面，切换部署模式为“创建 Office ISO”，并勾选下载后部署。

添加产品，按需选择，比如 Office 2021 专业增强版 - 批量许可证。

添加语言，按需选择，如果一个都不加，安装的时候依然需要联网。

根据需要修改体系结构和通道设置，其他设置可以按需更改。

**为了能够验证 Office 安装文件的完整性，我们建议您勾选「下载设置」-「下载后校验 Office 安装文件」。**

::: tip 提示
如果你需要为其他版本的 Windows 下载 Office，例如在 Windows 10 中下载 Office 安装包给 Windows 7 使用，请更改 *下载设置 - UA* 为对应系统版本，反之亦然。
:::

确认所有设置无误后，点击“开始部署”即可。

使用此方法创建的 Office ISO 包含默认配置，在 ISO 中双击打开 Office Tool Plus 时会询问用户是否开始 Office 的安装。

## 创建不含默认配置的 Office ISO

打开 Office Tool Plus，在部署页面，切换部署模式为“下载”。

添加产品，按需选择，比如 Office 2021 专业增强版 - 批量许可证。

添加语言，按需选择，如果一个都不加，安装的时候依然需要联网。

根据需要修改体系结构和通道设置，其他设置可以按需更改。

**为了能够验证 Office 安装文件的完整性，我们建议您勾选「下载设置」-「下载后校验 Office 安装文件」。**

::: tip 提示
如果你需要为其他版本的 Windows 下载 Office，例如在 Windows 10 中下载 Office 安装包给 Windows 7 使用，请更改 *下载设置 - UA* 为对应系统版本，反之亦然。
:::

确认所有设置无误后，点击“开始部署”即可开始下载。

下载完成后，按 F5 重置所有选项，也可以在「查看 XML 代码」的子菜单中找到「重置」选项。

然后切换部署模式为“创建 Office ISO”，点击开始部署即可。
